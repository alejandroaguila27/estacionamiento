<template>
    <div class="content-f">
        <div class="form">
            <div class="header">
                <h2>Editar Perfil</h2>
            </div>
            <div class="body">
                <form>
                    <div class="item">
                        <p class="one">Nombre de Usuario</p>
                        <input type="text">
                    </div>
                    <div class="item">
                        <p>Nombre de Estacionamiento</p>
                        <input type="text">
                    </div>
                    <div class="item">
                        <p>Correo</p>
                        <input type="email">
                    </div>
                    <div class="item">
                        <p>Contraseña</p>
                        <input type="password">
                    </div>
                    <div class="item">
                        <p>Confirmar Contraseña</p>
                        <input type="password">
                    </div>
                    <div class="item">
                        <p>Imagen de Perfil</p>
                        <input type="file">
                    </div>
                    <div class="btn">
                        <input type="button" value="Actualizar Datos">
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>

<script>
import '../assets/formlogin.css'
</script>