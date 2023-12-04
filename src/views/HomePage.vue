<script setup lang="ts">
import NavBar from '@/components/NavBar.vue';
import MainFooter from '@/components/MainFooter.vue'
import { RouterView } from "vue-router";
</script>
<template>
    <header>
        <NavBar />
    </header>
    <section>
        <RouterView />
    </section>
    <footer>
        <MainFooter />
    </footer>
</template>