<template>
  <main class="hero">
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
</style>
