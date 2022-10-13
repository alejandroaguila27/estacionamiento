<template>
    <div class="content-p">
        <div class="profile">
            <img src="../assets/img/profile.jpg" alt="Profile">
            <h4>Nombre de Usuario</h4>
            <p>Estacionamiento 1</p>
        </div>
        <div class="panel">
            <div class="item primary">
                <p><RouterLink to="/profile">Mi Perfil</RouterLink></p>
            </div>
            <div class="item">
                <p><RouterLink to="/create">Crear Usuario</RouterLink></p>
            </div>
            <div class="item">
                <p>Modificar usuarios</p>
            </div>
            <div class="item">
                <p>Validar tiempo</p>
            </div>
            <div class="item">
                <p>Generar Reporte</p>
            </div>
        </div>
    </div>
</template>

<script>
import '../assets/profilec.css'
import { RouterLink, RouterView } from 'vue-router'
</script>