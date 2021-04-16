<template>
  <main id="up" class="hero">
    <VueSlickCarousel
      :arrows="false"
      :dots="false"
      :infinite="false"
      :autoplay="false"
      :fade="true"
    >
      <div class="carousel-item">
        <div class="title-container">
          <h1 class="title">
            Muestra al mundo la<br /><span>anatomía</span><br />de tu marca
          </h1>
        </div>
      </div>
      <!-- <div class="carousel-item">
        <div class="title-container">
          <h1 class="title">
            Muestra al mundo la<br /><span>anatomía</span><br />de tu marca
          </h1>
        </div>
      </div>
      <div class="carousel-item">
        <div class="title-container">
          <h1 class="title">
            Muestra al mundo la<br /><span>anatomía</span><br />de tu marca
          </h1>
        </div>
      </div> -->
    </VueSlickCarousel>
  </main>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  components: { VueSlickCarousel },
}
</script>

<style scoped>
/* .bg-hero img {
  position: relative;
  z-index: 0;
  width: 100%;
} */
.carousel-item {
  background-image: url('@/assets/images/hero.jpg');
  background-repeat: no-repeat;
  /* background-size: cover; */
  height: 100vh;
  font-family: sifonn;
}
.title {
  font-size: 4rem;
  color: #fff;
  margin-left: 15rem;
  /* line-height: 8rem; */
  text-transform: uppercase;
}
.title-container {
  position: relative;
  top: 30%;
}
.title span {
  font-size: 15rem;
  text-transform: uppercase;
  line-height: 130px;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .carousel-item {
    background-size: cover;
  }
  .title {
    margin-left: 10rem;
  }
  .title span {
    font-size: 12rem;
  }
}
@media screen and (max-width: 1440px) {
}
@media screen and (max-width: 1280px) {
  .title {
    font-size: 3.5rem;
  }
  .title span {
    font-size: 11rem;
  }
}
@media screen and (max-width: 1024px) {
}
@media screen and (max-width: 768px) {
  .carousel-item {
    background-image: url('@/assets/images/hero-mobile.jpg');
  }
  .title-container {
    position: initial;
    margin-top: 20rem;
  }
  .title {
    margin-left: 0;
    text-align: center;
  }
  .title span {
    line-height: 110px;
  }
}
@media screen and (max-width: 576px) {
  .title {
    font-size: 2.5rem;
  }
  .title span {
    line-height: 80px;
    font-size: 9rem;
  }
  .title-container {
    margin-top: 30rem;
  }
}
@media screen and (max-width: 540px) {
  .title span {
    line-height: 70px;
    font-size: 8rem;
  }
  .title {
    font-size: 2rem;
  }
}
@media screen and (max-width: 480px) {
  .title span {
    line-height: 60px;
    font-size: 7rem;
  }
}
@media screen and (max-width: 426px) {
}
@media screen and (max-width: 376px) {
  .title span {
    line-height: 50px;
    font-size: 6rem;
  }
  .title {
    font-size: 1.7rem;
  }
}
@media screen and (max-width: 320px) {
  .title span {
    line-height: 55px;
    font-size: 5rem;
  }
  .title-container {
    margin-top: 20rem;
  }
}
</style>
