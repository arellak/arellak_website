<script setup>
import Projects from './Projects.vue';
import ProfilePhoto from './ProfilePhoto.vue';
</script>

<template>
    <div class="aboutContainer">
        <ProfilePhoto url="./profilepicture.png" alt="arellak profile photo"></ProfilePhoto>
        <div class="about-text">
            <h1>arellak</h1>
            <p>
                I'm a developer from Germany with focus on web development. On the other hand, I'm trying (and failing) to write my own game engine in C++ using RayLib.
                Passionate about Anime and Games.
                I enjoy creating solutions that embrace functionality and also tend to take way too much time to complete. Feel free to explore my portfolio further to see my work:
            </p>
        </div>
        <Projects></Projects>
    </div>
</template>

<style lang="scss" scoped>
.aboutContainer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    max-width: 90%;
    padding: 30px;
    margin: auto auto auto auto;
}

.about-text {
    h1 {
        color: #E94560;
        margin-bottom: 15px;
    }

    p {
        font-size: 1em;
        line-height: 1.5;
    }
}

</style>
