<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Carousel from '../components/Carousel.vue'
import { onMounted } from 'vue'

</script>

<template>
  <Carousel />

  <div class="container bg-secondary mt-5 d-flex flex-column justify-content-center">
    <h2>
      ¡Diviertete con tu familia completando divertidos retos personalizados!
    </h2>
    <p class="fs-5">
      ¡Inicia sesion para retar a familiares o amigos y así competir para ver quien es el mejor!
    </p>
    <div class="d-flex justify-content-center mb-3">
      <button class="btn btn-primary ">
        Iniciar Sesion
      </button>
    </div>
    <p>
      Diviertete completado divertidos retos personalizados por tus amigos o familia para conseguir puntos y asi poder
      intercambiarlos por recompensas personalizadas.
    </p>
    <p>
      Mas mensajes de este estilo, ahora no me viene la inspiración divina de antes de estar enfermo
    </p>
  </div>

  <div class="container-fluid mt-5">
    <div class="row justify-content-center align-items-start text-center">
      <div class="col-md-6">
        <div class="p-3 bg-danger">
          <h4 class="pt-2 pb-2">¿Que es famty?</h4>
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
        <div class="p-3 bg-warning">
          <h4 class="pt-2 pb-2">Sobre nosotros</h4>
          <p>
            Hola que tal
          </p>
        </div>
      </div>
    </div>
  </div>

</template>

<style scoped></style>