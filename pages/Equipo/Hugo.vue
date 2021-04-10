<template>
  <div class="team-container">
    <Navigation />
    <nuxt-link to="/españa#team" class="close-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="40"
        height="40"
        fill="#2D2D2D"
        class="bi bi-x-circle-fill"
        viewBox="0 0 16 16"
      >
        <path
          d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM5.354 4.646a.5.5 0 1 0-.708.708L7.293 8l-2.647 2.646a.5.5 0 0 0 .708.708L8 8.707l2.646 2.647a.5.5 0 0 0 .708-.708L8.707 8l2.647-2.646a.5.5 0 0 0-.708-.708L8 7.293 5.354 4.646z"
        />
      </svg>
    </nuxt-link>
    <section class="container">
      <div class="team-bar">
        <figure><img src="@/assets/images/hugo.png" alt="Hugo" /></figure>
        <h1 class="name">HUGO V.</h1>
        <p class="puesto">ESTRATEGA DE MARKETING</p>
      </div>
      <div class="description">
        <p>
          Hugo, mercadólogo con 20 años de experiencia en Marketing integral,
          especializado en inteligencia de mercados y creador de un sistema de
          unificación de publicidad y comercialización para marcas y proyectos.
        </p>
        <p>
          Hugo también es director del Festival de teatro Galerías con 5
          ediciones y director de teatro con 10 años de experiencia.
        </p>
        <div class="music">
          <VueSlickCarousel
            class="carousel-vtrv"
            :arrows="true"
            :dots="false"
            :infinite="true"
            :center-mode="true"
            :slides-to-show="1"
            :slides-to-scroll="1"
            :variable-width="true"
          >
            <div><img src="@/assets/mkt/1.png" alt="" /></div>
            <div><img src="@/assets/mkt/2.png" alt="" /></div>
            <div><img src="@/assets/mkt/3.png" alt="" /></div>
            <div><img src="@/assets/mkt/4.png" alt="" /></div>
            <div><img src="@/assets/mkt/5.png" alt="" /></div>
            <div><img src="@/assets/mkt/6.png" alt="" /></div>
            <div><img src="@/assets/mkt/7.png" alt="" /></div>
          </VueSlickCarousel>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  components: {
    Navigation,
    VueSlickCarousel,
  },
}
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.team-bar {
  background-color: var(--metodologia);
  background-image: url(@/assets/images/logo-mask.png);
  width: 60rem;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-flow: column;
  padding: 0 3rem;
}
.name {
  font-family: sifonn;
  font-size: 5rem;
  color: #fff;
  text-transform: uppercase;
  margin-top: 1rem;
}
.puesto {
  font-family: c-gothic;
  font-size: 2.6rem;
  color: #212121;
  text-transform: uppercase;
  margin-top: 3.5rem;
}
.description {
  font-family: c-gothic;
  font-size: 3rem;
  color: #212121;
  box-sizing: content-box;
  padding: 0 10rem;
  width: 60%;
  margin-bottom: 20rem;
}
.description p {
  margin: 4rem;
}
.close-icon {
  position: absolute;
  right: 0;
  margin: 20px;
}
.music {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.carousel-vtrv {
  width: 50%;
  position: absolute;
  top: 80%;
  left: 40%;
}
</style>
