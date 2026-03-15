<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Carousel from '../components/Carousel.vue'
import { onMounted } from 'vue'

</script>

<template>
  <Carousel />

  <div class="information-container">
    <div container-fluid class="d-flex justify-center align-middle text-center">
      <div class="col-6 bg-secondary">
        <p>Puto</p>
      </div>
      <div class="col-6 bg-primary">
        <p>Puta</p>
      </div>
    </div>
  </div>

</template>

<style scoped>
.information-container{
  margin-top: 2vh;
  background-color: black;
}
</style>