<template>
  <section id="servicios">
    <figure class="servicios">
      <img src="@/assets/images/servicios.svg" alt="Servicios" />
    </figure>
    <div>
      <CThemeProvider>
        <c-accordion
          :allow-multiple="true"
          :allow-toggle="true"
          class="container"
        >
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/MKT DIGITAL.svg" alt="mkt digital" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                marketing digital
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Análisis de data • Ingeniería de datos • Desarrollo de modelos de
              Machine Learning • Creación de estrategias SEO y SEM • Desarrollo
              de contenido • Gestión de campañas digitales • Segmentación •
              Community management
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/PUBLICIDAD.svg" alt="Publicidad" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                publicidad
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Campañas de branding • Campañas de lanzamiento • Campañas de
              temporalidades • Campañas de venta
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="@/assets/images/INVESTIGACION-MERCADOS.svg"
                  alt="investigación de mercados"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                investigación de mercados
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Análisis de data • Mistery shopper • Estudios de mercado •
              Definición de Buyer persona • Análisis cualitativo y cuantitativo
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/AUDIOVISUAL.svg" alt="audiovisual" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                producción audiovisual
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Comerciales • Video clips • Cineminutos Video corporativo • Video
              en estudio • Digital
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/BRANDING.svg" alt="branding" />
              </figure>
              <c-box flex="1" text-align="left" class="title"> branding </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Creatividad • Comunicación • Gestión de estrategias •
              Planificación y estructuración de marca • Creación de Identidad
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/WEB DESIGN.svg" alt="web design" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                web design
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Diseño o rediseño de web • Creación de contenidos • Hospedaje •
              Programación • SEO / SEM
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="@/assets/images/CENTRALMEDIOS.svg"
                  alt="central de medios"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                central de medios
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Tradicionales y digitales • Estrategias • Pautas • Negociación y
              compra • Seguimiento
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/DISEÑO.svg" alt="diseño" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                diseño e ilustración
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Conceptualización • Creación • Concepto gráfico • Análisis del
              color
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/FOTOGRAFIA.svg" alt="fotografía" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                fotografía
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Publicitaria • Producto • Documental • Moda • Editorial
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/MUSICA.svg" alt="musicalización" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                musicalización
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Composición Musical • Jingle • Spots radio • Diseño sonoro •
              Grabación en estudio • Mezcla • Sonido directo
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img
                  src="@/assets/images/CONTENIDOS.svg"
                  alt="análisis de data"
                />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                contenido
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              Digital • Editorial • Medios tradicionales
            </c-accordion-panel>
          </c-accordion-item>
          <c-accordion-item border="none">
            <c-accordion-header border="none" bg="white" class="vtrv-acordion">
              <figure class="image">
                <img src="@/assets/images/ANIMACION.svg" alt="animación" />
              </figure>
              <c-box flex="1" text-align="left" class="title">
                animación
              </c-box>
            </c-accordion-header>
            <c-accordion-panel pb="4" class="vtrv-text">
              2D • 3D • Stop motion • Motion graphics
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
</style>
