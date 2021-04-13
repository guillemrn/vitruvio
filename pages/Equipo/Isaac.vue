<template>
  <div class="team-container">
    <Navigation />
    <a class="close-icon" @click="$router.back()">
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
    </a>
    <section class="container">
      <div class="team-bar">
        <figure>
          <img src="https://i.imgur.com/wPjL4KP.png" alt="Isaac" />
        </figure>
        <h1 class="name">ISAAC R.</h1>
        <p class="puesto">Físico y analista de data</p>
      </div>
      <div class="description">
        <p>
          Isaac es un analista de datos por Centrogeo conacyt. Experto en la
          optimización de presupuesto, problemas de ruteo, movilidad y
          logística.
        </p>
        <p>
          Isaac ha ganado concursos sobre emprendimiento social y científicos en
          universidades Top de USA como MIT, Boston collage y Loyola Marymount
          University y ha trabajado para marcas como: DIDI Mobility, IBM y
          Logrand Entretainment Group.
        </p>
      </div>
    </section>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  components: {
    Navigation,
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
.video {
  font-family: c-gothic;
  font-size: 3rem;
  color: #212121;
  box-sizing: content-box;
  width: 60%;
  margin-bottom: 20rem;
}
.video iframe {
  text-align: center;
  border-radius: 1rem;
}
.close-icon {
  position: absolute;
  right: 0;
  margin: 20px;
}
.music,
.video {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.carousel-vtrv {
  width: 60%;
  position: absolute;
  top: 80%;
  left: 35%;
}
</style>
