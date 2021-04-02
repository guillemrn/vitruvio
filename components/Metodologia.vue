<template>
  <section id="metodologia" class="section-container">
    <figure class="metodologia">
      <img src="@/assets/images/metodologia.svg" alt="metodologia" />
    </figure>
    <div class="container">
      <div class="text-container a">
        <div>
          <h3>proyección</h3>
          <p>EJECUCIÓN Y MEDICIÓN<br />DE RESULTADOS</p>
        </div>
        <div>
          <h3>mente</h3>
          <p>ANÁLISIS Y<br />DIAGNÓSTICO DE MARCA</p>
        </div>
      </div>
      <figure class="lisa">
        <img src="@/assets/images/lisa.svg" alt="Mona Lisa" />
        <hr />
      </figure>
      <div class="text-container b">
        <div>
          <h3>corazón</h3>
          <p>CONCEPTUALIZACIÓN<br />CREATIVA</p>
        </div>
        <div>
          <h3>sentidos</h3>
          <p>ELABORACIÓN DE<br />ESTRATEGIA DE COMUNICACIÓN</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.section-container {
  padding: 5rem 0;
}
.metodologia {
  margin: 10rem 0 2rem 10rem;
}
section {
  background-color: var(--metodologia);
  color: #fff;
}
h3 {
  font-family: sifonn;
  font-size: 5rem;
  text-transform: uppercase;
}
p {
  font-family: c-gothic;
  font-size: 3rem;
  text-transform: uppercase;
}
.lisa {
  display: flex;
  align-items: center;
  justify-content: center;
}
.lisa img {
  position: relative;
  z-index: 1;
}
hr {
  width: 80%;
  position: absolute;
  z-index: 0;
  border: 2px solid white;
}
.text-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 0 15rem;
  text-align: center;
}
.a {
  position: relative;
  bottom: -30rem;
}
.b {
  position: relative;
  bottom: 30rem;
}
</style>
