<template>
  <main>
    <h1 class="title">
      PARA AYUDARTE A TENER UNA MEJOR EXPERIENCIA, POR FAVOR DINOS
    </h1>
    <h1 class="subtitle">¿DE DÓNDE NOS VISITAS?</h1>
    <div class="container">
      <figure><img src="@/assets/images/map.png" alt="map" /></figure>
      <div class="cta">
        <nuxt-link to="/mexico">
          <input id="dewey" type="radio" name="drone" value="dewey" />
          <label for="dewey">México</label>
        </nuxt-link>
        <nuxt-link to="/españa">
          <input id="dewey" type="radio" name="drone" value="dewey" />
          <label for="dewey">España</label>
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
label {
  font-family: b-gothic;
  font-size: 8rem;
  color: #fff;
  text-transform: uppercase;
}
.cta {
  display: flex;
  flex-flow: column;
}
</style>
