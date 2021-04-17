<template>
  <section id="servicios">
    <figure class="servicios">
      <img src="https://i.imgur.com/fVbKkrm.png" alt="Servicios" />
    </figure>
    <div>
      <CThemeProvider>
        <c-accordion :allow-toggle="true" :default-index="[]" class="container">
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/2WsNNki.png" alt="mkt digital" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                marketing digital
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Análisis de data • Ingeniería de datos • Desarrollo de modelos
              de Machine Learning • Creación de estrategias SEO y SEM • Creación
              de contenido • Gestión de campañas digitales • Segmentación •
              Community management
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image publi-img">
                <img src="https://i.imgur.com/COanPPj.png" alt="Publicidad" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                publicidad
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Campañas de branding • Campañas de lanzamiento • Campañas de
              temporalidades • Campañas de venta
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="https://i.imgur.com/XYotYCB.png"
                  alt="investigación de mercados"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                investigación de mercados
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Análisis de data • Mistery shopper • Estudios de mercado •
              Definición de Buyer persona • Análisis cualitativo y cuantitativo
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/fFnFCax.png" alt="audiovisual" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                producción audiovisual
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Comerciales • Video clips • Cineminutos • Video corporativo •
              Video en estudio • Digital
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/DASiifT.png" alt="branding" />
              </figure>
              <c-box flex="1" text-align="left" class="title"> branding </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Creatividad • Comunicación • Gestión de estrategias •
              Planificación y estructuración de marca • Creación de Identidad
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/fnB3nNy.png" alt="web design" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                web design
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Diseño o rediseño de web • Creación de contenidos • Hospedaje •
              Programación • SEO / SEM
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="https://i.imgur.com/YVPn1aE.png"
                  alt="central de medios"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                central de medios
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Tradicionales y digitales • Estrategias • Pautas • Negociación y
              compra • Seguimiento
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/rdvrdKp.png" alt="diseño" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                diseño e ilustración
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Conceptualización • Creación • Concepto gráfico • Análisis del
              color
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/fQ4s4vx.png" alt="fotografía" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                fotografía
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Publicitaria • Producto • Documental • Moda • Editorial
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="https://i.imgur.com/7lJJiXp.png"
                  alt="musicalización"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                musicalización
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Composición Musical • Jingle • Spots radio • Diseño sonoro •
              Grabación en estudio • Mezcla • Sonido directo
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="https://i.imgur.com/0ERu9uD.png"
                  alt="análisis de data"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                contenido
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • Digital • Editorial • Medios tradicionales
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="https://i.imgur.com/qq3lnPZ.png" alt="animación" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                animación
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              • 2D • 3D • Stop motion • Motion graphics
            </c-accordion-panel>
          </c-accordion-item>
        </c-accordion>
      </CThemeProvider>
    </div>
  </section>
</template>

<script>
import {
  CThemeProvider,
  CAccordion,
  CAccordionItem,
  CAccordionHeader,
  CAccordionPanel,
} from '@chakra-ui/vue'

export default {
  name: 'DefaultLayout',
  components: {
    CThemeProvider,
    CAccordion,
    CAccordionItem,
    CAccordionHeader,
    CAccordionPanel,
  },
}
</script>

<style scoped>
.servicios {
  margin: 15rem 0 2rem 10rem;
}
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  align-items: center;
  text-align: center;
  margin: 4rem;
}
.title {
  font-family: sifonn;
  font-size: 4.5rem;
  color: var(--title-services);
  text-transform: uppercase;
  margin: 2rem 0;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
}
.image {
  display: flex;
  justify-content: center;
  align-items: center;
}
.vtrv-acordion {
  flex-flow: column;
  height: 396px;
}
.vtrv-acordion:focus {
  box-shadow: initial;
}
.vtrv-acordion:hover {
  background-color: rgba(235, 44, 139, 0.1);
  cursor: pointer;
}
.vtrv-text {
  font-family: c-gothic;
  font-size: 1.6rem;
  background-color: var(--title-services);
  height: 16rem !important;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  padding: 2rem;
  -webkit-box-shadow: inset 0px 10px 30px -10px rgb(0 0 0 / 75%);
  -moz-box-shadow: inset 0px 10px 30px -10px rgb(0 0 0 / 75%);
  box-shadow: inset 0px 10px 30px -10px rgb(0 0 0 / 75%);
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .container {
    margin: 2rem;
  }
  .title {
    font-size: 3.5rem;
  }
  .servicios {
    margin: 12rem 0 5rem 10rem;
  }
}
@media screen and (max-width: 1440px) {
  .vtrv-text {
    font-size: 1.4rem;
  }
}
@media screen and (max-width: 1280px) {
  .servicios {
    margin: 10rem 0 5rem 5rem;
  }
  .title {
    font-size: 3rem;
  }
}
@media screen and (max-width: 1200px) {
  .container {
    grid-template-columns: repeat(3, 1fr);
  }
}
@media screen and (max-width: 1024px) {
  .vtrv-text {
    font-size: 1.4rem;
  }
  .container {
    grid-template-columns: repeat(3, 1fr);
  }
  .servicios {
    margin: 8rem 0 5rem 3rem;
  }
}
@media screen and (max-width: 1000px) {
  .container {
    grid-template-columns: repeat(2, 1fr);
  }
}
@media screen and (max-width: 768px) {
  .container {
    grid-template-columns: repeat(2, 1fr);
  }
  .servicios img {
    width: 45rem;
  }
}
@media screen and (max-width: 700px) {
  .container {
    grid-template-columns: repeat(1, 1fr);
  }
}
@media screen and (max-width: 576px) {
  .container {
    grid-template-columns: repeat(1, 1fr);
  }
  .servicios img {
    width: 40rem;
  }
}
@media screen and (max-width: 540px) {
  .servicios img {
    width: 35rem;
  }
  .vtrv-acordion {
    height: auto;
  }
}
@media screen and (max-width: 480px) {
  .servicios img {
    width: 30rem;
  }
}
@media screen and (max-width: 426px) {
}
@media screen and (max-width: 376px) {
  .servicios img {
    width: 22rem;
  }
  .title {
    font-size: 2.5rem;
  }
  .image img {
    width: 16rem;
  }
  .publi-img img {
    width: 28rem;
  }
}
@media screen and (max-width: 320px) {
  .servicios img {
    width: 18rem;
  }
  .title {
    font-size: 2.2rem;
  }
  .image img {
    width: 14rem;
  }
  .publi-img img {
    width: 26rem;
  }
}
</style>
