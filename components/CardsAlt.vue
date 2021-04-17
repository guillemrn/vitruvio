<template>
  <section class="container">
    <div class="cards">
      <div class="card">
        <div class="title">
          <h2>arranque<br /><span class="subtitle">digital</span></h2>
        </div>
        <ul class="description">
          <li>Pixel de seguimiento de hasta 4 canales digitales.</li>
          <li>Configuración de google analytics.</li>
          <li>
            Configuración de eventos de seguimiento en google tag manager.
          </li>
          <li>
            Análisis web y recomendaciones de costumer journey (recorrido del
            cliente).
          </li>
          <li>Reporte mensual.</li>
        </ul>
      </div>
      <div class="card">
        <div class="title">
          <h2>arranque de<br /><span class="subtitle-2">contenido</span></h2>
        </div>
        <ul class="description ab">
          <li>Producción audiovisual.</li>
          <li>Producción fotográfica.</li>
          <li>Rebranding.</li>
          <li>Herramientas de venta digitales.</li>
        </ul>
      </div>
      <div class="card">
        <div class="title">
          <h2>otros<br /><span class="subtitle-3">servicios</span></h2>
        </div>
        <ul class="description">
          <li>Estudio de mercado.</li>
          <li>Optimización web.</li>
          <li>
            Implementación de software de atención al cliente según necesidades.
          </li>
          <li>CRM.</li>
        </ul>
      </div>
    </div>
    <figure class="girl">
      <img
        src="@/assets/images/Girl-with-a-Pearl.png"
        alt="Girl with a pearl"
      />
    </figure>
  </section>
</template>

<style scoped>
.container {
  background-color: var(--yellow);
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 10rem;
}
.card {
  width: 1035px;
  height: 300px;
  margin: 4rem 0 4rem 7.5rem;
  display: inline-flex;
  align-items: center;
  background-color: #fff;
  height: 30rem;
  -webkit-box-shadow: -6px 8px 26px -10px rgb(0 0 0 / 65%);
  -moz-box-shadow: -6px 8px 26px -10px rgb(0 0 0 / 65%);
  box-shadow: -6px 8px 26px -10px rgb(0 0 0 / 65%);
  box-sizing: border-box;
}
.title {
  width: 250px;
  background-color: var(--cards);
  font-family: sifonn;
  height: inherit;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 0 1rem;
}
h2 {
  font-size: 2rem;
  color: #fff;
  text-transform: uppercase;
  text-align: center;
}
h2 .subtitle {
  font-size: 4rem;
}
h2 .subtitle-2 {
  font-size: 3.5rem;
}
h2 .subtitle-3 {
  font-size: 3.7rem;
}
.description {
  margin: 2rem;
}
.description li {
  list-style: none;
  margin: 2rem;
  color: var(--nav-text);
  font-family: c-gothic;
  font-size: 2rem;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .container {
    margin-top: 9rem;
  }
  .card {
    width: 90rem;
    height: 28rem;
  }
  .girl img {
    width: 50rem;
  }
  .title {
    width: 20rem;
  }
  h2 .subtitle {
    font-size: 4.5rem;
  }
  h2 .subtitle-2 {
    font-size: 3rem;
  }
  h2 .subtitle-3 {
    font-size: 3.6rem;
  }
}
@media screen and (max-width: 1440px) {
  .girl img {
    width: 40rem;
  }
  .card {
    margin: 2rem 0 2rem 5rem;
  }
  h2 {
    font-size: 1.8rem;
  }
  h2 .subtitle-2 {
    font-size: 2.5rem;
  }
}
@media screen and (max-width: 1366px) {
  .cards {
    margin: 5rem 0;
  }
  .container {
    margin-top: -2rem;
  }
  .description li {
    margin: 1rem;
    font-size: 1.8rem;
  }
}
@media screen and (max-width: 1280px) {
  .container {
    margin-top: 10rem;
  }
  .girl img {
    display: none;
  }
  .cards {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
  }
  .card {
    margin: 4rem 0 4rem 7.5rem;
  }
}
@media screen and (max-width: 1024px) {
  .container {
    margin-top: 0;
  }
  .cards {
    position: relative;
    z-index: 1;
  }
}
@media screen and (max-width: 768px) {
  .card {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    width: 60rem;
    margin: 4rem 0 4rem 8rem;
    height: 30rem;
  }
  .title {
    width: inherit;
  }
  h2 .subtitle-2 {
    font-size: 3.5rem;
  }
  .ab {
    margin-left: -25rem;
  }
}
@media screen and (max-width: 576px) {
  .card {
    width: 40rem;
    margin: 4rem 0 4rem 8rem;
    height: 30rem;
  }
  .ab {
    margin-left: initial;
  }
  .description li {
    font-size: 1.6rem;
  }
}
@media screen and (max-width: 540px) {
  .card {
    margin: 4rem 0 4rem 7rem;
  }
  .description li {
    font-size: 1.4rem;
  }
}
@media screen and (max-width: 480px) {
  .card {
    margin: 4rem 0 4rem 4rem;
  }
}
@media screen and (max-width: 426px) {
  .card {
    width: 35rem;
  }
  .cards {
    position: relative;
    z-index: 1;
  }
}
@media screen and (max-width: 376px) {
  .cards {
    margin-top: 10rem;
    position: relative;
    z-index: 1;
  }
  .card {
    width: 32rem;
    margin: 4rem 0 4rem 3rem;
  }
}
@media screen and (max-width: 320px) {
  .card {
    width: 25rem;
    margin: 4rem 0 4rem 3rem;
  }
  .description li {
    font-size: 1.2rem;
  }
}
</style>
