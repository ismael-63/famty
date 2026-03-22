<script setup>

</script>

<template>
    <div class="login_container d-flex justify-content-center align-items-center">
        <div class="login-card">
            <h2 class="login-title">Iniciar Sesión</h2>
            <form action="">
                <div class="form-group">
                    <label for="username">Usuario</label>
                    <input type="text" id="username" class="form-input" placeholder="Ingresa tu usuario" />
                </div>
                <div class="form-group">
                    <label for="password">Contraseña</label>
                    <input type="password" id="password" class="form-input" placeholder="Ingresa tu contraseña">
                </div>
                <button type="submit" class="login-btn">Entrar</button>
            </form>
            <p class="register-link">¿No tienes cuenta? <a href="#">Regístrate</a></p>
        </div>
    </div>
</template>

<style scoped>
.login_container {
    min-height: 100vh;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

</style>