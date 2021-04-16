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
          <img src="https://i.imgur.com/TgatKJ9.png" alt="Diana" />
        </figure>
        <h1 class="name">diana t.</h1>
        <p class="puesto">fotógrafa</p>
        <p class="description">
          Diana es una fotógrafa con más de 9 años de experiencia en fotografía
          comercial y de retrato. Ha sido directora de fotografía editorial en
          diferentes revistas y maneja la gerencia de un estudio de fotografía
          en Guadalajara.
        </p>
        <p class="description">
          Su ojo crítico y gran experiencia, hacen de sus fotografías el
          elemento clave de cualquier campaña publicitaria.
        </p>
      </div>
      <div class="video">
        <iframe
          width="660"
          height="415"
          src="https://www.youtube.com/embed/L6kUmGUWrxA"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
          rel="0"
          showinfo="0"
        ></iframe>
        <div class="music">
          <VueSlickCarousel
            v-bind="settings"
            class="carousel-vtrv"
            :arrows="true"
            :dots="false"
            :infinite="true"
            :center-mode="true"
            :slides-to-show="1"
            :slides-to-scroll="1"
            :variable-width="true"
          >
            <div><img src="@/assets/fotografia/1.png" alt="" /></div>
            <div><img src="@/assets/fotografia/2.png" alt="" /></div>
            <div><img src="@/assets/fotografia/3.png" alt="" /></div>
            <div><img src="@/assets/fotografia/5.png" alt="" /></div>
            <div><img src="@/assets/fotografia/6.png" alt="" /></div>
            <div><img src="@/assets/fotografia/7.png" alt="" /></div>
            <div><img src="@/assets/fotografia/8.png" alt="" /></div>
            <div><img src="@/assets/fotografia/9.png" alt="" /></div>
            <div><img src="@/assets/fotografia/10.png" alt="" /></div>
            <div><img src="@/assets/fotografia/11.png" alt="" /></div>
            <div><img src="@/assets/fotografia/12.png" alt="" /></div>
            <div><img src="@/assets/fotografia/13.png" alt="" /></div>
            <div><img src="@/assets/fotografia/14.png" alt="" /></div>
            <div><img src="@/assets/fotografia/15.png" alt="" /></div>
            <div><img src="@/assets/fotografia/16.png" alt="" /></div>
            <div><img src="@/assets/fotografia/17.png" alt="" /></div>
            <div><img src="@/assets/fotografia/18.png" alt="" /></div>
            <div><img src="@/assets/fotografia/19.png" alt="" /></div>
            <div><img src="@/assets/fotografia/20.png" alt="" /></div>
            <div><img src="@/assets/fotografia/21.png" alt="" /></div>
            <div><img src="@/assets/fotografia/22.png" alt="" /></div>
            <div><img src="@/assets/fotografia/23.png" alt="" /></div>
            <div><img src="@/assets/fotografia/24.png" alt="" /></div>
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
  data() {
    return {
      settings: {
        responsive: [
          {
            breakpoint: 480,
            settings: {
              variableWidth: false,
              initialSlide: 7,
            },
          },
        ],
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
  width: 660px;
  height: 415px;
}
.close-icon {
  position: absolute;
  right: 0;
  margin: 20px;
  cursor: pointer;
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
    left: 36%;
  }
  .carousel-vtrv img {
    height: 20rem;
  }
}
@media screen and (max-width: 1440px) {
  .video iframe {
    width: 55rem;
    height: 35rem;
  }
  .carousel-vtrv {
    left: 37%;
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
    font-size: 2.4rem;
  }
  .description {
    font-size: 1.5rem;
  }
}
@media screen and (max-width: 1280px) {
}
@media screen and (max-width: 1024px) {
  .video iframe {
    width: 45rem;
    height: 25rem;
  }
  .team-bar {
    width: 40rem;
  }
  .puesto {
    font-size: 2rem;
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
    top: 160%;
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
    top: 160%;
  }
}
@media screen and (max-width: 540px) {
  .carousel-vtrv {
    left: 11%;
    top: 160%;
    padding: 0 2rem;
  }
  .carousel-vtrv img {
    height: 19rem;
  }
  .slick-prev,
  .slick-next {
    top: 25%;
  }
}
@media screen and (max-width: 480px) {
  .carousel-vtrv {
    top: 170%;
  }
}
@media screen and (max-width: 426px) {
  .carousel-vtrv {
    top: 180%;
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
  .carousel-vtrv {
    top: 170%;
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
  .carousel-vtrv {
    top: 250%;
  }
}
</style>
