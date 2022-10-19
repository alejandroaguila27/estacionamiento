<template>
  <Nav/>
  <router-view/>
</template>
<script>
  import './assets/base.css'
  import { RouterLink, RouterView } from 'vue-router'
  import Nav from './components/Nav.vue'
  export default{
      components: { Nav }
    }
</script>