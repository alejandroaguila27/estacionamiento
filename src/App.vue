<template>
  <nav>
    <RouterLink to="/">
      Home
    </RouterLink>
    <RouterLink to="/login">
      Login
    </RouterLink>
    <RouterLink to="/profile">
      profile
    </RouterLink>
    <RouterLink to="/about">
      About
    </RouterLink>
  </nav>
  <router-view/>
</template>
<script setup>
import { RouterLink, RouterView } from 'vue-router'
import './assets/base.css'
</script>


