<template>
    <div class="content">
      <profile/>  
      <form-login/>
    </div>
</template>

<script>
    import '../assets/profile.css'
    import Profile from '../components/Profile.vue';
    import FormLogin from '../components/FormLogin.vue'
    export default{
        components: { Profile, FormLogin }
    }
</script>
