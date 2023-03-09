<script setup lang="ts">

import { ref } from 'vue';

const count = ref(0)
const title = ref("Home App")

function increment() {
    count.value++
}

</script>

<template>
    <h1 @click=increment>{{ title }} ({{ count }})</h1>
</template>

<style scoped>

</style>