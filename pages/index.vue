<template>
  <main>
    <h1 class="title">
      PARA AYUDARTE A TENER UNA MEJOR EXPERIENCIA, POR FAVOR DINOS
    </h1>
    <h1 class="subtitle">¿DE DÓNDE NOS VISITAS?</h1>
    <div class="container">
      <figure><img src="@/assets/images/map.png" alt="map" /></figure>
      <div class="cta">
        <nuxt-link to="/mexico" class="mx">
          <div>México</div>
        </nuxt-link>
        <nuxt-link to="/españa" class="spain">
          España
          <span>y fuera de méxico</span>
        </nuxt-link>
      </div>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: var(--yellow);
  padding: 8rem 4rem;
  height: 100%;
}
.title {
  font-family: c-gothic;
  font-size: 3.7rem;
  text-align: center;
  color: #fff;
  margin-bottom: 2rem;
}
.subtitle {
  font-family: sifonn;
  font-size: 10rem;
  text-align: center;
  color: #fff;
}
.container {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
figure {
  margin-top: 6rem;
}
.cta {
  display: flex;
  flex-flow: column;
  text-transform: uppercase;
}
.mx,
.spain {
  font-family: b-gothic;
  font-size: 4rem;
  color: #fff;
  text-decoration: none;
  border: 2px solid #fff;
  margin: 2rem;
  text-align: center;
  border-radius: 60px;
  transition: 300ms;
}
.mx:hover {
  background-color: #ec008c;
  color: var(--yellow);
}
.spain:hover {
  background-color: #ec008c;
  color: var(--yellow);
}
.mx {
  padding: 1.7rem 4rem;
}
.spain {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-flow: column;
  padding: 1rem 4rem;
}
.spain span {
  font-family: c-gothic;
  font-size: 1.5rem;
  margin-top: -0.5rem;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
}
@media screen and (max-width: 1440px) {
  .title {
    font-size: 3.4rem;
  }
  .subtitle {
    font-size: 8rem;
  }
  .container img {
    width: 85rem;
  }
  .mx,
  .spain {
    font-size: 3.8rem;
  }
  .spain span {
    font-size: 1.4rem;
  }
}
@media screen and (max-width: 1280px) {
  .title {
    font-size: 3.2rem;
  }
  .container img {
    width: 80rem;
  }
  .mx,
  .spain {
    font-size: 3.7rem;
  }
}
@media screen and (max-width: 1024px) {
  main {
    padding: 8rem 2rem;
  }
  .title {
    font-size: 2.8rem;
  }
  .subtitle {
    font-size: 6rem;
  }
  .container img {
    width: 70rem;
  }
  .mx,
  .spain {
    font-size: 3.4rem;
  }
  .spain span {
    font-size: 1.2rem;
  }
}
@media screen and (max-width: 768px) {
  .container img {
    display: none;
  }
  main {
    background-image: url('@/assets/images/map-mov.png');
    background-repeat: no-repeat;
    background-position: bottom;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    padding: 8rem 4rem;
  }
  .cta {
    margin-top: 3rem;
  }
  .mx,
  .spain {
    font-size: 4rem;
  }
  .spain span {
    font-size: 1.5rem;
  }
  .title {
    font-size: 2.5rem;
  }
  .subtitle {
    font-size: 7rem;
    text-align: left;
    margin-left: 12rem;
  }
}
@media screen and (max-width: 576px) {
  main {
    padding: 8rem 2rem;
  }
  .mx,
  .spain {
    font-size: 3.8rem;
  }
  .spain span {
    font-size: 1.4rem;
  }
  .title {
    font-size: 2rem;
    margin-top: 5rem;
  }
  .subtitle {
    font-size: 5rem;
    margin-left: 11rem;
  }
}
@media screen and (max-width: 540px) {
  main {
    background-position-x: -100px;
  }
  .mx,
  .spain {
    font-size: 3.6rem;
  }
  .spain span {
    font-size: 1.3rem;
  }
  .title {
    font-size: 1.8rem;
  }
  .subtitle {
    font-size: 4.6rem;
    margin-left: 10rem;
  }
}
@media screen and (max-width: 480px) {
  .mx,
  .spain {
    font-size: 3.4rem;
  }
  .spain span {
    font-size: 1.2rem;
  }
  .title {
    font-size: 1.6rem;
  }
  .subtitle {
    font-size: 4rem;
    margin-left: 10rem;
  }
}
@media screen and (max-width: 426px) {
  .title {
    font-size: 1.4rem;
  }
  .subtitle {
    font-size: 4rem;
    margin-left: 6rem;
  }
}
@media screen and (max-width: 376px) {
  .title {
    font-size: 1.2rem;
  }
  .subtitle {
    margin-left: 4rem;
  }
}
@media screen and (max-width: 320px) {
  .title {
    font-size: 1rem;
  }
  .subtitle {
    margin-left: 3rem;
    font-size: 3.4rem;
  }
}
</style>
