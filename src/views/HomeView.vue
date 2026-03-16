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
    <button class="btn btn-primary ">
      Iniciar Sesion
    </button>
  </div>

  <div class="information-container">
    <div container-fluid class="d-flex justify-center align-middle text-center">
      <div class="col-6 bg-secondary">
        <p>Alga</p>
      </div>
      <div class="col-6 bg-primary">
        <p>algo</p>
      </div>
    </div>
  </div>

</template>

<style scoped>
.information-container {
  margin-top: 2vh;
  background-color: black;
}
</style>