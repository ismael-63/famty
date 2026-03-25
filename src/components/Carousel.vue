<template>
  <div class="carousel-wrapper">
    <div id="carouselId" class="carousel slide modern-carousel" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselId" data-bs-slide-to="0" class="active" aria-current="true"
          aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselId" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselId" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="4000">
          <img src="/src/assets/img/fondo.png" class="d-block w-100" alt="Fondo principal">
          <div class="carousel-caption">
            <h5>Bienvenido a Famty</h5>
            <p>Retos divertidos para toda la familia</p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="1000">
          <img src="/src/assets/img/algo.jpg" class="d-block w-100" alt="Algo">
          <div class="carousel-caption">
            <h5>Desafíos Personalizados</h5>
            <p>Crea retos únicos para tus seres queridos</p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="1000">
          <img src="/src/assets/img/pinto.jpg" class="d-block w-100" alt="Pinto">
          <div class="carousel-caption">
            <h5>Competencia Amigable</h5>
            <p>Gana puntos y recompensas</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselId" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>

      <button class="carousel-control-next" type="button" data-bs-target="#carouselId" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<style scoped>
.carousel-wrapper {
  position: relative;
  overflow: hidden;
}

.modern-carousel {
  width: 100%;
  max-width: 100vw;
  margin: 0;
}

.carousel-item {
  width: 100%;
  height: 70vh;
  position: relative;
}

.carousel-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
}

.carousel-caption {
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.8), rgba(118, 75, 162, 0.8));
  border-radius: 15px;
  padding: 1rem 1.5rem;
  bottom: 5vh;
  left: 50%;
  transform: translateX(-50%);
  text-align: center;
  color: white;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
}

.carousel-caption h5 {
  font-size: 1.5rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
}

.carousel-caption p {
  font-size: 1rem;
  margin: 0;
  opacity: 0.9;
}

.carousel-indicators button {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.5);
  border: none;
  margin: 0 5px;
  transition: all 0.3s ease;
}

.carousel-indicators button.active {
  background-color: #ff6b6b;
  transform: scale(1.2);
}

.carousel-control-prev,
.carousel-control-next {
  width: 5%;
  opacity: 0.8;
  transition: opacity 0.3s ease;
}

.carousel-control-prev:hover,
.carousel-control-next:hover {
  opacity: 1;
}

.carousel-control-prev-icon,
.carousel-control-next-icon {
  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 50%;
  padding: 10px;
  transition: background-color 0.3s ease;
}

.carousel-control-prev-icon:hover,
.carousel-control-next-icon:hover {
  background-color: rgba(255, 255, 255, 1);
}
</style>