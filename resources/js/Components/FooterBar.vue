<script setup>
import { computed } from "vue";
import { containerMaxW } from "@/config.js";
import BaseLevel from "@/Components/BaseLevel.vue";
import JustboilLogo from "@/Components/JustboilLogo.vue";

const year = computed(() => new Date().getFullYear());
</script>

<template>
    <footer class="py-2 px-6">
        <BaseLevel :class="containerMaxW">
            <div class="text-center md:text-left">
                <h4>2020</h4>
            </div>
            <div class="md:py-2">
                <h4>Joyboy</h4>
            </div>
        </BaseLevel>
    </footer>
</template>
