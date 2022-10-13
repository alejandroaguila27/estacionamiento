<template>
    <div class="content">
        <h1>Inicio de Sesión</h1>
        <h4>Ingresa con nosotros para administrar tu estacionamiento</h4>
        <form>
            <div class="item">
                <input type="text" placeholder="Usuario" id="user">
            </div>
            <div class="item">
                <input type="password" placeholder="Contraseña" id="pass">
            </div>
            <div class="item-secondary">
                <div class="item-s">
                    <input type="checkbox" class="check" id="remember" name="remember" value="true">
                    <label for="remember">Recuerdame</label>
                </div>
                <div class="item-s">
                    <a href="http://">Olvidaste tu Contraseña</a>
                </div>
            </div>
            <div class="btn">
                <input type="button" value="Iniciar Sesión">
            </div>
        </form>
    </div>
</template>

<script>
import '../assets/login.css'
</script>