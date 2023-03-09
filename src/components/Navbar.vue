<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
    <header>
        <span>Logo</span>
        <nav>
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
        </nav>
    </header>
</template>

<style scoped>
header {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 0.5rem 1.5rem;
    background: var(--color-background-navbar);
    box-shadow: 0 1px 4px rgba(0, 0, 0, 25%);
}

span {
    color: var(--color-text-white);
}

nav {
    display: flex;
    flex-direction: row;
}

a {
    appearance: none;
    text-decoration: none;
    padding: 1rem;
    color: var(--color-text-white);
    border-right: 1px solid var(--color-text-white);
}

a:hover {
    background: var(--wh-black-3);
}

a:last-child {
    border-right: none;
}
</style>
