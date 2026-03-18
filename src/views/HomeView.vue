<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Carousel from '../components/Carousel.vue'
import { onMounted } from 'vue'

</script>

<template>
  <Carousel />

  <div class="main-section">
    <div class="container mt-5 d-flex flex-column justify-content-center text-center">
      <h1 class="main-title">
        ¡Diviertete con tu familia completando divertidos retos personalizados!
      </h1>
      <p class="main-subtitle">
        ¡Inicia sesion para retar a familiares o amigos y así competir para ver quien es el mejor!
      </p>
      <div class="d-flex justify-content-center mb-4">
        <button class="login-btn">
          Iniciar Sesion
        </button>
      </div>
      <p class="main-description">
        Diviertete completado divertidos retos personalizados por tus amigos o familia para conseguir puntos y asi poder
        intercambiarlos por recompensas personalizadas.
      </p>
      <p class="main-description">
        Mas mensajes de este estilo, ahora no me viene la inspiración divina de antes de estar enfermo
      </p>
    </div>
  </div>

  <div class="container-fluid mt-5">
    <div class="row justify-content-center align-items-start text-center">
      <div class="col-md-6">
        <div class="info-card">
          <h4 class="card-title">¿Que es famty?</h4>
          <p>
            Famty es una aplicación web donde poder poner retos personalizados para tus amigos o familia.
          </p>
          <p>
            Puedes retar a tus amigos con retos que inventeis y establecer recompensas a cambio o ver quien consigue
            completar mas retos que el resto.
          </p>
          <p>
            Puedes dinamizar el hacer las tareas del hogar para tus hijos o familares gracias a los retos, llevando un
            seguimiento de quien los cumple y establecer recompensas a traves del sistema de puntos.
          </p>
          <p>
            Mas cosas cuando regrese la inspiracion divina
          </p>
        </div>
      </div>
      <div class="col-md-6">
        <div class="info-card">
          <h4 class="card-title">Sobre nosotros</h4>
          <p>
            Este es un proyecto realizado por una sola persona con la intención de recordar las tecnologias usadas para
            crear esta página web
          </p>
          <p>
            Esta creada en mis ratos libres pero intentando mantener una constancia
          </p>
          <p>
            El proyecto avanza de forma muy lenta y con muchas rectificaciones pero avanza, que es lo importante
          </p>
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped>
.main-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 4rem 0;
  
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
}

.main-title {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

.main-subtitle {
  font-size: 1.25rem;
  margin-bottom: 2rem;
  opacity: 0.9;
}

.login-btn {
  background: linear-gradient(45deg, #ff6b6b, #ffa500);
  border: none;
  color: white;
  padding: 12px 30px;
  font-size: 1.1rem;
  font-weight: 600;
  border-radius: 50px;
  box-shadow: 0 4px 15px rgba(255, 107, 107, 0.4);
  transition: all 0.3s ease;
  cursor: pointer;
}

.login-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(255, 107, 107, 0.6);
  background: linear-gradient(45deg, #ffa500, #ff6b6b);
}

.main-description {
  font-size: 1rem;
  opacity: 0.8;
  max-width: 600px;
  margin: 0 auto 1rem;
}

.info-card {
  background: linear-gradient(145deg, #ffffff, #f8f9fa);
  border-radius: 20px;
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
  padding: 2rem;
  margin: 1rem;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.info-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 35px rgba(0, 0, 0, 0.15);
}

.card-title {
  font-size: 1.5rem;
  font-weight: 600;
  color: #333;
  margin-bottom: 1rem;
  position: relative;
}

.card-title::after {
  content: '';
  position: absolute;
  bottom: -5px;
  left: 50%;
  transform: translateX(-50%);
  width: 50px;
  height: 3px;
  background: linear-gradient(45deg, #667eea, #764ba2);
  border-radius: 2px;
}

.info-card p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.info-card p:last-child {
  margin-bottom: 0;
}
</style>