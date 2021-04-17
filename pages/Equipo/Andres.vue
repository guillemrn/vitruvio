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
          <img src="https://i.imgur.com/W2OP5mY.png" alt="Andrés" />
        </figure>
        <h1 class="name">andrés v.</h1>
        <p class="puesto">Animador y diseñador gráfico</p>
        <p class="description">
          Andrés es un animador digital especialista en motion graphics. Su
          formación como diseñador ha otorgado a sus animaciones una estética
          única, en la que se destacan su creación de personajes, ambientes y
          tipografías.
        </p>
        <p class="description">
          Andrés ha trabajado para marcas como HDI, Chiva cola, Petchoice y es
          colaborador de distintos estudios de animación en Guadalajara y CDMX.
        </p>
      </div>
      <div class="videoContainer">
        <VueSlickCarousel v-bind="settings" class="carousel-vtrv">
          <div>
            <iframe
              class="video-vtrv"
              src="https://www.youtube.com/embed/bAJA-4bUQnA"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
              rel="0"
              showinfo="0"
            ></iframe>
          </div>
          <div>
            <video controls class="video-vtrv">
              <source src="https://i.imgur.com/Gv4T1pT.mp4" type="video/mp4" />
            </video>
          </div>
          <div>
            <video controls class="video-vtrv">
              <source src="https://i.imgur.com/PAUBU7M.mp4" type="video/mp4" />
            </video>
          </div>
          <div>
            <video controls class="video-vtrv">
              <source src="@/assets/animacion/4.mp4" type="video/mp4" />
            </video>
          </div>
          <div>
            <video controls class="video-vtrv">
              <source src="@/assets/animacion/2.mp4" type="video/mp4" />
            </video>
          </div>
        </VueSlickCarousel>
        <!-- <div class="music">
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
            <div><img src="@/assets/animacion/1.png" alt="" /></div>
            <div><img src="@/assets/animacion/2.png" alt="" /></div>
            <div><img src="@/assets/animacion/3.png" alt="" /></div>
            <div><img src="@/assets/animacion/4.png" alt="" /></div>
          </VueSlickCarousel>
        </div> -->
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
  data() {
    return {
      settings: {
        arrows: true,
        dots: true,
        dotsClas: 'slick-dots custom-dot-class',
        edgeFrictio: 0.35,
        infinite: true,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
      },
    }
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
  font-size: 1.6rem;
  color: #fff;
  margin-top: 5rem;
}
.close-icon {
  position: absolute;
  right: 0;
  margin: 20px;
  cursor: pointer;
}
.carousel-vtrv {
  width: 50%;
  position: absolute;
  top: 35%;
  left: 40%;
}
.videoContainer {
  text-align: center;
}
.videoContainer .video-vtrv {
  border-radius: 1rem;
  width: 70rem;
  height: 45rem;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .video iframe {
    width: 60rem;
    height: 40rem;
  }
  .team-bar {
    width: 50rem;
  }
  .team-bar img {
    width: 25rem;
  }
  .name {
    font-size: 4rem;
  }
  .carousel-vtrv {
    left: 42%;
  }
  .carousel-vtrv img {
    height: 20rem;
  }
  .videoContainer .video-vtrv {
    border-radius: 1rem;
    width: 60rem;
    height: 40rem;
  }
  .puesto {
    font-size: 2.4rem;
  }
}
@media screen and (max-width: 1440px) {
  .videoContainer .video-vtrv {
    width: 55rem;
    height: 35rem;
  }
  .carousel-vtrv {
    left: 42%;
  }
  .carousel-vtrv img {
    height: 18rem;
  }
}
@media screen and (max-width: 1366px) {
  .video iframe {
    width: 50rem;
    height: 30rem;
  }
  .carousel-vtrv {
    left: 40%;
    width: 55%;
  }
  .carousel-vtrv img {
    height: 18rem;
  }
  .team-bar {
    width: 45rem;
  }
  .team-bar img {
    width: 20rem;
  }
  .name {
    font-size: 3.5rem;
  }
  .puesto {
    font-size: 2.2rem;
  }
  .description {
    font-size: 1.5rem;
  }
}
@media screen and (max-width: 1280px) {
}
@media screen and (max-width: 1024px) {
  .team-bar {
    width: 40rem;
  }
  .puesto {
    font-size: 1.8rem;
  }
  .carousel-vtrv {
    left: 44%;
    width: 52%;
  }
}
@media screen and (max-width: 768px) {
  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
  }
  .team-bar {
    width: 100vw;
  }
  .carousel-vtrv {
    left: 5%;
    width: 90%;
    top: 120%;
  }
  .carousel-vtrv img {
    height: 22rem;
  }
  .video {
    margin-top: 5rem;
    margin-bottom: 0;
  }
}
@media screen and (max-width: 576px) {
  .carousel-vtrv {
    left: 10%;
    width: 80%;
    top: 120%;
  }
  .videoContainer .video-vtrv {
    width: 45rem;
    height: 30rem;
  }
}
@media screen and (max-width: 540px) {
  .carousel-vtrv {
    left: 11%;
    padding: 0 2rem;
  }
  .carousel-vtrv img {
    height: 19rem;
  }
  .slick-prev,
  .slick-next {
    top: 25%;
  }
  .videoContainer .video-vtrv {
    width: 38rem;
    height: 28rem;
  }
}
@media screen and (max-width: 480px) {
  .videoContainer .video-vtrv {
    width: 30rem;
    height: 20rem;
  }
}
@media screen and (max-width: 426px) {
  .videoContainer .video-vtrv {
    width: 28rem;
    height: 20rem;
  }
  .carousel-vtrv {
    top: 130%;
  }
}
@media screen and (max-width: 376px) {
  .team-bar img {
    width: 18rem;
  }
  .name {
    font-size: 3rem;
  }
  .puesto {
    font-size: 1.8rem;
  }
  .description {
    font-size: 1.4rem;
  }
  .videoContainer .video-vtrv {
    width: 25rem;
    height: 15rem;
  }
}
@media screen and (max-width: 320px) {
  .name {
    font-size: 2.5rem;
  }
  .puesto {
    font-size: 1.6em;
  }
  .team-bar {
    width: 100vw;
    height: 100%;
    padding: 4rem 2rem;
  }
  .videoContainer .video-vtrv {
    width: 20rem;
    height: 15rem;
  }
  .carousel-vtrv {
    top: 170%;
  }
}
</style>
