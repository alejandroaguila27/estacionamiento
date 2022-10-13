<template>
    <div class="content">
        <profile/> 
        <new-user/>
    </div>
</template>

<script>
    import Profile from '../components/Profile.vue';
    import NewUser from '../components/NewUser.vue';
    import '../assets/newuser.css'
    export default{
        components: { Profile, NewUser }
    }
</script>