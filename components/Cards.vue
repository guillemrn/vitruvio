<template>
  <div class="container">
    <figure class="bg-image">
      <img src="@/assets/images/bg-paquetes.png" alt="background" />
    </figure>
    <div class="title-cnt">
      <h1 class="title">paquetes digital</h1>
    </div>
    <section class="cards-container">
      <div class="card">
        <div class="card-title-container">
          <div class="polygon-1"></div>
          <h2 class="card-title">básico</h2>
          <div class="polygon-2"></div>
        </div>
        <ul class="cardlist-2">
          <li>Estrategia Digital.</li>
          <li>Creación de campañas y conceptos de comunicación.</li>
          <li>
            Marketing operacional: creación de campañas, segmentación en canales
            A/B testing, traking 360 y campañas de remarketing.
          </li>
          <li>
            Contenido digital en formatos: diseño, video y copy. (Hasta 2
            publicaciones semanales).
          </li>
          <li>
            Manejo de hasta 2 canales digitales según la estrategia y el
            segmento.
          </li>
          <li>Gestión comunitaria.</li>
          <li>Calendario mensual de contenido.</li>
          <li>Ejecutiva o ejecutivo de cuenta.</li>
          <li>Un Reporte mensual.</li>
        </ul>
        <div class="card-price-container">
          <!-- <h3 class="card-price">€ 3,200</h3> -->
        </div>
      </div>
      <div class="card">
        <div class="card-title-container">
          <div class="polygon-3"></div>
          <h2 class="card-title">premium</h2>
          <div class="polygon-4"></div>
        </div>
        <ul class="cardlist-2">
          <li>Estrategia Digital.</li>
          <li>Creación de campañas y conceptos de comunicación.</li>
          <li>
            Marketing operacional: creación de campañas, segmentación en canales
            A/B testing, traking 360 y campañas de remarketing.
          </li>
          <li>
            Contenido digital en formatos: diseño, video y copy. (Hasta 3
            publicaciones semanales).
          </li>
          <li>
            Manejo de hasta 3 canales digitales según la estrategia y el
            segmento.
          </li>
          <li>Gestión comunitaria.</li>
          <li>Calendario mensual de contenido.</li>
          <li>Ejecutiva o ejecutivo de cuenta.</li>
          <li>Dos reportes mensuales.</li>
        </ul>
        <div class="card-price-container">
          <!-- <h3 class="card-price">€ 4,200</h3> -->
        </div>
      </div>
      <div class="card">
        <div class="card-title-container">
          <div class="polygon-5"></div>
          <h2 class="card-title">premium plus</h2>
          <div class="polygon-6"></div>
        </div>
        <ul class="cardlist-3">
          <li>
            Análisis de datos en tiempo real de hasta 4 canales digitales.
          </li>
          <li>Optimización de campañas con IA.</li>
          <li>Estrategia digital.</li>
          <li>Creación de campañas y conceptos de comunicación.</li>
          <li>
            Marketing operacional: creación de campañas, segmentación en canales
            A/B testing, traking 360 y campañas de remarketing.
          </li>
          <li>
            Contenido digital en formatos: diseño, ilustración, motion graphics,
            video y copy. (Hasta 4 publicaciones semanales).
          </li>
          <li>
            Manejo de hasta 4 canales digitales según la estrategia y el
            segmento.
          </li>
          <li>Instalación de pixel de seguimiento.</li>
          <li>Gestión comunitaria.</li>
          <li>Calendario mensual de contenido.</li>
          <li>Ejecutiva o ejecutivo de cuenta.</li>
          <li>Dos reportes mensuales.</li>
        </ul>
        <div class="card-price-container">
          <!-- <h3 class="card-price">€ 5,200</h3> -->
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.container {
  background-color: #ffd634;
  /* background-image: url('@/assets/images/bg-paquetes.png');
  background-size: cover; */
  height: 100%;
}
.bg-image img {
  position: absolute;
  z-index: 0;
  width: 100%;
}
.title-cnt {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  z-index: 1;
}
.title {
  padding: 1rem 4rem;
  background-color: var(--metodologia);
  color: #fff;
  font-size: 4rem;
  font-family: sifonn;
  text-transform: uppercase;
  width: fit-content;
  text-align: center;
  margin-top: 4rem;
}
.cards-container {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin: 6rem 0;
  position: relative;
  z-index: 1;
}
.card {
  width: 49rem;
  height: 79rem;
  background-color: #fff;
  -webkit-box-shadow: -15px 20px 38px -8px rgba(0, 0, 0, 0.65);
  -moz-box-shadow: -15px 20px 38px -8px rgba(0, 0, 0, 0.65);
  box-shadow: -15px 20px 38px -8px rgba(0, 0, 0, 0.65);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-flow: column;
}
.card-title-container {
  background-color: var(--metodologia);
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 550px;
  margin-top: -5rem;
  padding: 1.5rem;
  -webkit-box-shadow: 0px 43px 9px -39px rgb(0 0 0 / 75%);
  -moz-box-shadow: 0px 43px 9px -39px rgb(0 0 0 / 75%);
  box-shadow: 0px 43px 9px -39px rgb(0 0 0 / 75%);
}
.polygon-1 {
  clip-path: polygon(100% 0, 0 0, 100% 100%);
  width: 3rem;
  height: 3rem;
  background-color: var(--cards);
  position: relative;
  left: -32.4%;
  top: 108.1%;
}
.polygon-2 {
  clip-path: polygon(100% 0, 0 0, 0 100%);
  width: 3rem;
  height: 3rem;
  background-color: var(--cards);
  position: relative;
  left: 32.3%;
  top: 108.1%;
}
.polygon-3 {
  clip-path: polygon(100% 0, 0 0, 100% 100%);
  width: 3rem;
  height: 3rem;
  background-color: var(--cards);
  position: relative;
  left: -28.3%;
  top: 108.1%;
}
.polygon-4 {
  clip-path: polygon(100% 0, 0 0, 0 100%);
  width: 3rem;
  height: 3rem;
  background-color: var(--cards);
  position: relative;
  left: 28.5%;
  top: 108.1%;
}
.polygon-5 {
  clip-path: polygon(100% 0, 0 0, 100% 100%);
  width: 3rem;
  height: 3rem;
  background-color: var(--cards);
  position: relative;
  left: -17%;
  top: 108.1%;
}
.polygon-6 {
  clip-path: polygon(100% 0, 0 0, 0 100%);
  width: 3rem;
  height: 3rem;
  background-color: var(--cards);
  position: relative;
  left: 17%;
  top: 108.1%;
}
.card-title {
  font-size: 4rem;
  font-family: sifonn;
  text-transform: uppercase;
  text-align: center;
}
ul {
  position: relative;
  top: 5%;
}
ul li {
  font-family: c-gothic;
  font-size: 1.5rem;
  color: var(--nav-text);
  margin: 3rem 3rem 3rem 6rem;
}
.card-price-container {
  background-color: var(--cards);
  color: #fff;
  width: inherit;
  position: relative;
  bottom: -13%;
}
.card-price {
  font-family: b-gothic;
  font-size: 8rem;
  text-align: center;
}
.cardlist-2 li {
  margin: 2.3rem 3rem 2rem 6rem;
}
.cardlist-3 li {
  margin: 1rem 3rem 0.8rem 6rem;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .card {
    width: 39rem;
    height: 60rem;
  }
  .card-title-container {
    color: #fff;
    width: 43rem;
    margin-top: 5rem;
  }
  .card-title {
    font-size: 3rem;
  }
  ul li {
    font-size: 1.4rem;
    color: var(--nav-text);
  }
  .card-price-container {
    bottom: -10%;
  }
  .cardlist-1 li {
    margin: 2.5rem 2.5rem 2.5rem 6rem;
  }
  .cardlist-2 li {
    margin: 2.25rem 3rem 2rem 6rem;
  }
  .cardlist-3 li {
    margin: 0.9rem 3rem 0.8rem 6rem;
  }
  .polygon-1 {
    width: 2rem;
    height: 2rem;
    left: -34%;
    top: 112%;
  }
  .polygon-2 {
    width: 2rem;
    height: 2rem;
    left: 34%;
    top: 112%;
  }
  .polygon-3 {
    width: 2rem;
    height: 2rem;
    left: -30%;
    top: 112%;
  }
  .polygon-4 {
    width: 2rem;
    height: 2rem;
    left: 30%;
    top: 112%;
  }
  .polygon-5 {
    width: 2rem;
    height: 2rem;
    left: -19%;
    top: 112%;
  }
  .polygon-6 {
    width: 2rem;
    height: 2rem;
    left: 19%;
    top: 112%;
  }
  .card-price {
    font-size: 7rem;
  }
}
@media screen and (max-width: 1440px) {
  .card {
    width: 39rem;
    height: 55rem;
  }
  .card-title-container {
    margin-top: 2rem;
  }
  ul li {
    font-size: 1.2rem;
  }
  .cardlist-1 li {
    margin: 2.2rem 2.2rem 2.2rem 6rem;
  }
  .cardlist-2 li {
    margin: 1.4rem 2rem 1.6rem 6rem;
  }
  .cardlist-3 li {
    margin: 0.6rem 3rem 0.65rem 6rem;
  }
}
@media screen and (max-width: 1280px) {
  .card-title-container {
    margin-top: 0;
  }
  .card {
    width: 30rem;
    height: 55rem;
  }
  .cardlist-1 li {
    margin: 1.5rem 1.5rem 1.5rem 2.5rem;
  }
  .cardlist-2 li {
    margin: 1.2rem 2rem 1.3rem 2.5rem;
  }
  .cardlist-3 li {
    margin: 0.4rem 1.4rem 0.3rem 2.5rem;
  }
  .card-title-container {
    width: 34rem;
  }
  .card-price {
    font-size: 5rem;
  }
  .title {
    margin-top: 2rem;
    font-size: 3rem;
  }
  .cards-container {
    margin: 3rem 0;
  }
  .polygon-1 {
    left: -30%;
  }
  .polygon-2 {
    left: 30%;
  }
  .polygon-3 {
    left: -25%;
  }
  .polygon-4 {
    left: 25%;
  }
  .polygon-5 {
    left: -10.5%;
  }
  .polygon-6 {
    left: 10.5%;
  }
}
@media screen and (max-width: 1024px) {
  .title {
    margin-top: 4rem;
    font-size: 4rem;
  }
  .cards-container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
  }
  .cards-container .card {
    margin: 4rem;
  }
  .bg-image img {
    height: 270%;
  }
  .cardlist-1 li {
    margin: 2rem 2rem 2rem 2.5rem;
  }
  .cardlist-2 li {
    margin: 1.2rem 2rem 1.3rem 2.5rem;
  }
  .cardlist-3 li {
    margin: 0.6rem 1.4rem 0.4rem 2.5rem;
  }
  ul li {
    font-size: 1.3rem;
  }
}
@media screen and (max-width: 768px) {
  .bg-image img {
    height: 220%;
  }
}
@media screen and (max-width: 576px) {
  .bg-image img {
    height: 350%;
  }
}
@media screen and (max-width: 540px) {
  .title {
    font-size: 3rem;
  }
}
@media screen and (max-width: 480px) {
}
@media screen and (max-width: 426px) {
  .bg-image img {
    height: 300%;
  }
}
@media screen and (max-width: 376px) {
  .title {
    font-size: 2.5rem;
  }
  .card-title {
    font-size: 2.5rem;
  }
  .polygon-1 {
    left: -33%;
    top: 127%;
  }
  .polygon-2 {
    left: 33%;
    top: 127%;
  }
  .polygon-3 {
    left: -28.5%;
    top: 127%;
  }
  .polygon-4 {
    left: 28.5%;
    top: 127%;
  }
  .polygon-5 {
    left: -17%;
    top: 127%;
  }
  .polygon-6 {
    left: 17%;
    top: 127%;
  }
  .bg-image img {
    height: 343%;
  }
}
@media screen and (max-width: 320px) {
  .title {
    font-size: 2rem;
  }
  .card {
    width: 25rem;
    height: 60rem;
  }
  .card-title-container {
    width: 29rem;
  }
  .bg-image img {
    height: 290%;
  }
  .polygon-1 {
    left: -30%;
  }
  .polygon-2 {
    left: 30%;
  }
  .polygon-3 {
    left: -25%;
  }
  .polygon-4 {
    left: 25%;
  }
  .polygon-5 {
    left: -10.5%;
  }
  .polygon-6 {
    left: 10.5%;
  }
  .bg-image img {
    height: 390%;
  }
}
</style>
