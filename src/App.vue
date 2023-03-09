<script setup lang="ts">
import { RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Main from './components/Main.vue'
</script>

<template>
    <section class="app">
        <Navbar />
        <Main>
            <RouterView />
        </Main>
    </section>
</template>
