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
  height: 100vh;
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
</style>
