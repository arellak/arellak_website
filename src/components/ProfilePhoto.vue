<script setup>
const props = defineProps({
    url: {
        type: String,
        required: true,
    },
    alt: {
        type: String,
        required: true,
    }
});
</script>

<template>
<div class="profile-photo">
    <img :src="props.url" :alt="props.alt">
</div>
</template>

<style lang="scss">
.profile-photo {
    img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        margin-bottom: 20px;
        border: 3px solid #0F3460;
    } 
}
</style>
