<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import { onMounted } from 'vue'

</script>

<template>
  <div class="d-flex carousel-container">
    <div id="carouselId" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="4000">
          <img src="/src/assets/img/fondo.png" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item" data-bs-interval="1000">
          <img src="/src/assets/img/algo.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item" data-bs-interval="1000">
          <img src="/src/assets/img/pinto.jpg" class="d-block w-100" alt="...">
        </div>
      </div>
    </div>
  </div>

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

#carouselId {
  width: 100vw;
  margin-left: calc(-50vw + 50%);
  margin-right: calc(-50vw + 50% - 2rem);

}

.carousel-item {
  width: 100%;
  height: 60vh;
}

.carousel-item img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center;

}
</style>