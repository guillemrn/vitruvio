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
        <figure><img src="@/assets/images/kenji.png" alt="Kenji" /></figure>
        <h1 class="name">KENJI K.</h1>
        <p class="puesto">COMPOSITOR / MULTI INSTRUMENTISTA</p>
      </div>
      <div class="description">
        <p>
          Kenji, ha compuesto la música de los largometrajes Somos Mari Pepa
          (2013), Los Años Azules (2016), Ocho de cada diez (2018), Cigüeñas
          (2018) y Los Lobos (2019). Así como de los documentales El último
          bolero, Derecho de Playa y La Hora de la Siesta.
        </p>
        <p>
          Kenji estuvo nominado al Ariel por Mejor Música Original por la
          película Somos Mari Pepa. Es contrabajista y compositor de Ensamble
          Supercluster, agrupación dedicada a la música de cámara contemporánea.
          Fue seleccionado Talents de la Berlinale 2020.
        </p>
        <div class="music">
          <iframe
            src="https://open.spotify.com/embed/artist/1DaitxoiQBh1fAKsoN4tpg"
            width="300"
            height="380"
            frameborder="0"
            allowtransparency="true"
            allow="encrypted-media"
          ></iframe>
          <iframe
            src="https://open.spotify.com/embed/artist/3W7rB9hcCzHWp5Lh8RZO5Z"
            width="300"
            height="380"
            frameborder="0"
            allowtransparency="true"
            allow="encrypted-media"
          ></iframe>
        </div>
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
</style>
