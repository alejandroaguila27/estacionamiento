<template>
    <nav>
        <RouterLink to="/">
            Home
        </RouterLink>
        <RouterLink to="/login">
            Login
        </RouterLink>
        <RouterLink to="/about">
            About
        </RouterLink>
    </nav>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import '../assets/nav.css'
</script>