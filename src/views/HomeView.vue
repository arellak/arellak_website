<script setup>
import "../assets/main.scss";
import About from "../components/About.vue";
import Footer from "../components/Footer.vue";
</script>

<template>
    <div class="homeContainer">
        <About></About>
        <Footer></Footer>
    </div>
</template>

<style lang="scss">
.homeContainer {
    display: flex;
    flex-direction: column;
    margin: 0 auto 0 auto;
    max-width: 800px;
    background-color: #16213E;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.6);
}

</style>
