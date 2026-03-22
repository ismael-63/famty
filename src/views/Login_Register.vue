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

.login-card {
    background: linear-gradient(145deg, #ffffff, #f8f9fa);
    border-radius: 20px;
    box-shadow: 0 12px 40px rgba(0, 0, 0, 0.2);
    padding: 3rem 2.5rem;
    width: 100%;
    max-width: 400px;
    border: 1px solid rgba(255, 255, 255, 0.2);
}

.login-title {
    font-size: 2rem;
    font-weight: 700;
    color: #333;
    text-align: center;
    margin-bottom: 2rem;
    background: linear-gradient(45deg, #667eea, #764ba2);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    font-weight: 600;
    color: #333;
    margin-bottom: 0.5rem;
    font-size: 0.95rem;
}

.form-input {
    width: 100%;
    padding: 12px 15px;
    border: 2px solid #e0e0e0;
    border-radius: 10px;
    font-size: 1rem;
    transition: all 0.3s ease;
    background: white;
    color: #333;
}

.form-input:focus {
    outline: none;
    border-color: #667eea;
    box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
    background: #f8fafb;
}

.form-input::placeholder {
    color: #999;
}

.login-btn {
    width: 100%;
    padding: 12px 30px;
    background: linear-gradient(45deg, #667eea, #764ba2);
    border: none;
    color: white;
    font-size: 1.1rem;
    font-weight: 600;
    border-radius: 10px;
    margin-top: 1rem;
    transition: all 0.3s ease;
    cursor: pointer;
    box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);
}

.login-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 25px rgba(102, 126, 234, 0.6);
}

.login-btn:active {
    transform: translateY(0);
}

.register-link {
    text-align: center;
    margin-top: 1.5rem;
    color: #666;
    font-size: 0.95rem;
}

.register-link a {
    color: #667eea;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
}

.register-link a:hover {
    color: #764ba2;
    text-decoration: underline;
}
</style>