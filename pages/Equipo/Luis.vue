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
          <img src="https://i.imgur.com/Sa7jGgz.png" alt="Luis" />
        </figure>
        <h1 class="name">LUIS ANTONIO A.</h1>
        <p class="puesto">CINEASTA / DIRECTOR CREATIVO</p>
        <p class="description">
          Luis, es un egresado de la Universidad de Guadalajara, con
          licenciatura en Artes Audiovisuales. Ha trabajado como director
          creativo en agencias de publicidad para marcas como: Menú local,
          Erdinger, UNE, Balones Molten, Vimifos, entre otras.
        </p>
        <p class="description">
          Durante su carrera como cineasta ha sido seleccionado en el SHORT FILM
          CORNNER, del festival de Cannes 2020, así como en la selección oficial
          de SHORTS MÉXICO 2020, con su cortometraje ERÓ, el cual recibió el
          premio a mejor guión en categoría de ficción.
        </p>
      </div>
      <div class="video">
        <iframe
          width="660"
          height="415"
          src="https://www.youtube.com/embed/eKOgBG07tv4"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
          rel="0"
          showinfo="0"
        ></iframe>
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
            <div><img src="@/assets/audiovisual/1.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/2.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/3.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/4.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/5.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/6.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/7.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/8.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/9.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/10.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/11.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/12.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/13.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/14.png" alt="" /></div>
            <div><img src="@/assets/audiovisual/15.png" alt="" /></div>
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
