<template>
  <div class="container">
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
        <ul>
          <li>Estrategia digital.</li>
          <li>Creación de campañas y conceptos de comunicación.</li>
          <li>
            Marketing operacional: creación de campañas, segmentación en canales
            A/B Testing, tracking 360 y campañas de remarketing.
          </li>
          <li>
            Contenido digital (2) formato: Diseño, video, copy Manejo de hasta 2
            canales digitales según la estrategia y el segmento de la marca.
          </li>
          <li>Community management.</li>
          <li>Ejecutiva o ejecutivo de cuenta.</li>
          <li>Reporte mensual.</li>
        </ul>
        <div class="card-price-container">
          <h3 class="card-price">€ 3,200</h3>
        </div>
      </div>
      <div class="card">
        <div class="card-title-container">
          <div class="polygon-3"></div>
          <h2 class="card-title">premium</h2>
          <div class="polygon-4"></div>
        </div>
        <ul class="cardlist-2">
          <li>Estrategia digital.</li>
          <li>Creación de campañas y conceptos de comunicación.</li>
          <li>
            Marketing operacional: creación de campañas, segmentación en canales
            A/B Testing, tracking 360 y campañas de remarketing en hasta 3
            canales digitales.
          </li>
          <li>
            Manejo de hasta 3 canales digitales según la estrategia y el
            segmento de la marca.
          </li>
          <li>
            Contenido digital (3) formato: Diseño, video, copy Calendario
            digital.
          </li>
          <li>Ejecutiva o ejecutivo de cuenta.</li>
          <li>Community management.</li>
          <li>Dos reportes mensuales.</li>
        </ul>
        <div class="card-price-container">
          <h3 class="card-price">€ 4,200</h3>
        </div>
      </div>
      <div class="card">
        <div class="card-title-container">
          <div class="polygon-5"></div>
          <h2 class="card-title">premium plus</h2>
          <div class="polygon-6"></div>
        </div>
        <ul class="cardlist-3">
          <li>Análisis de data en tiempo real de hasta 4 canales digitales.</li>
          <li>Optimización de campañas con IA</li>
          <li>Estrategia digital.</li>
          <li>Creación de campañas y conceptos de comunicación.</li>
          <li>
            Marketing operacional: creación de campañas, segmentación en canales
            A/B Testing, tracking 360 y campañas de remarketing.
          </li>
          <li>
            Contenido digital (4) formato: Diseño, ilustración, motion graphics,
            video, copy
          </li>
          <li>Calendario digital.</li>
          <li>
            Manejo de hasta 4 canales digitales según la estrategia y el
            segmento de la marca.
          </li>
          <li>Instalación de pixel de seguimiento.</li>
          <li>Community management.</li>
          <li>Ejecutiva o ejecutivo de cuenta.</li>
          <li>Dos reportes mensuales.</li>
        </ul>
        <div class="card-price-container">
          <h3 class="card-price">€ 5,200</h3>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.container {
  background-color: #ffd634;
  background-image: url('@/assets/images/bg-paquetes.png');
  background-size: cover;
  height: 100vh;
}
.title-cnt {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  top: 2.5%;
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
}
.cards-container {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin-top: 5rem;
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
</style>
