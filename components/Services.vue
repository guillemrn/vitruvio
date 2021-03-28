<template>
  <section>
    <figure class="servicios">
      <img src="@/assets/images/servicios.svg" alt="Servicios" />
    </figure>
    <div class="container">
      <div class="item">
        <figure>
          <img src="@/assets/images/MKT DIGITAL.svg" alt="mkt digital" />
        </figure>
        <h3>marketing digital</h3>
        <ul>
          <li>Análisis de data</li>
          <li>Ingeniería de datos</li>
          <li>Desarrollo de modelos de Machine Learning</li>
          <li>Creación de estrategias SEO y SEM</li>
          <li>Desarrollo de contenido</li>
          <li>Gestión de campañas digitales</li>
          <li>Segmentación</li>
          <li>Community management</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/PUBLICIDAD.svg" alt="mkt digital" />
        </figure>
        <h3>publicidad</h3>
        <ul>
          <li>Campañas de branding</li>
          <li>Campañas de lanzamiento</li>
          <li>Campañas de temporalidades</li>
          <li>Campañas de venta</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img
            src="@/assets/images/INVESTIGACION-MERCADOS.svg"
            alt="investigación de mercados"
          />
        </figure>
        <h3>investigación de mercados</h3>
        <ul>
          <li>Análisis de data</li>
          <li>Mistery shopper</li>
          <li>Estudios de mercado</li>
          <li>Definición de Buyer persona</li>
          <li>Análisis cualitativo y cuantitativo</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/AUDIOVISUAL.svg" alt="audiovisual" />
        </figure>
        <h3>producción audiovisual</h3>
        <ul>
          <li>Comerciales</li>
          <li>Video clips</li>
          <li>Cineminutos</li>
          <li>Video corporativo</li>
          <li>Video en estudio</li>
          <li>Digital</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/BRANDING.svg" alt="branding" />
        </figure>
        <h3>branding</h3>
        <ul>
          <li>Creatividad</li>
          <li>Comunicación</li>
          <li>Gestión de estrategias</li>
          <li>Planificación y estructuración de marca</li>
          <li>Creación de Identidad</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/WEB DESIGN.svg" alt="web design" />
        </figure>
        <h3>web design</h3>
        <ul>
          <li>Diseño o rediseño de web</li>
          <li>Creación de contenidos</li>
          <li>Hospedaje</li>
          <li>Programación</li>
          <li>SEO / SEM</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img
            src="@/assets/images/CENTRALMEDIOS.svg"
            alt="central de medios"
          />
        </figure>
        <h3>central de medios</h3>
        <ul>
          <li>Tradicionales y digitales</li>
          <li>Estrategias</li>
          <li>Pautas</li>
          <li>Negociación y compra</li>
          <li>Seguimiento</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/DISEÑO.svg" alt="diseño" />
        </figure>
        <h3>diseño e ilustración</h3>
        <ul>
          <li>Conceptualización</li>
          <li>Creación</li>
          <li>Concepto gráfico</li>
          <li>Análisis del color</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/FOTOGRAFIA.svg" alt="fotografía" />
        </figure>
        <h3>fotografía</h3>
        <ul>
          <li>Publicitaria</li>
          <li>Producto</li>
          <li>Documental</li>
          <li>Moda</li>
          <li>Editorial</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/MUSICA.svg" alt="musicalización" />
        </figure>
        <h3>musicalización</h3>
        <ul>
          <li>Composición Musical</li>
          <li>Jingle</li>
          <li>Spots radio</li>
          <li>Diseño sonoro</li>
          <li>Grabación en estudio</li>
          <li>Mezcla</li>
          <li>Sonido directo</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/CONTENIDOS.svg" alt="análisis de data" />
        </figure>
        <h3>análisis de data</h3>
        <ul>
          <li>2D</li>
          <li>3D</li>
          <li>Stop motion</li>
          <li>Motion graphics</li>
        </ul>
      </div>
      <div class="item">
        <figure>
          <img src="@/assets/images/ANIMACION.svg" alt="animación" />
        </figure>
        <h3>animación</h3>
        <ul>
          <li>Digital</li>
          <li>Editorial</li>
          <li>Medios tradicionales</li>
        </ul>
      </div>
    </div>
  </section>
</template>

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
.item {
  width: 350px;
  height: 620px;
}
h3 {
  font-family: sifonn;
  font-size: 4.5rem;
  color: var(--title-services);
  text-transform: uppercase;
  margin: 2rem 0;
}
ul {
  list-style: square;
  text-align: initial;
  margin: 0 6rem;
}
ul li {
  font-family: 'Century gothic';
  font-size: 1.8rem;
  text-align: start;
  color: var(--text-grid);
}
</style>
