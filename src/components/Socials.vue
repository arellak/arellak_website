<script setup>
import GitHubIcon from "./icons/IconGithub.vue";
import EmailIcon from "./icons/IconEmail.vue";
import TelegramIcon from "./icons/IconTelegram.vue";
</script>

<template>
    <div class="socialsContainer">
        <GitHubIcon username="arellak" />
        <EmailIcon email="marcel@arellak.de" />
        <TelegramIcon username="arellak" />
    </div>
</template>

<style lang="scss">
.socialsContainer {
    display: flex;
    flex-wrap: wrap;
    margin: 0.5em auto 0.5em auto;
    align-items: center;
    justify-content: center;
    gap: 10px;
}

.socialIcon {
    a {
        svg {
            width: 90%;
            path {
                fill: #E94560;
                transition: fill 0.4s ease;
            }

            &:hover {
                path {
                    fill: #9c2f40;
                    transition: transform 0.4s ease, fill 0.4s ease, opacity 0.4s ease;
                }
            }
        }
    }
}

</style>
