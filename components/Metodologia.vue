<template>
  <section id="metodologia" class="section-container">
    <figure class="metodologia">
      <img src="https://i.imgur.com/JLlTHXE.png" alt="metodologia" />
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
        <img src="@/assets/images/lisa.png" alt="Mona Lisa" />
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
  margin: 5rem 0 2rem 10rem;
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
  margin: 0 10rem;
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

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .lisa img {
    width: 70rem;
  }
  .text-container {
    margin: 0 6rem;
  }
  h3 {
    font-size: 4.5rem;
  }
  p {
    font-size: 2.5rem;
  }
}
@media screen and (max-width: 1440px) {
  .lisa img {
    width: 65rem;
  }
  h3 {
    font-size: 4rem;
  }
  p {
    font-size: 2rem;
  }
}
@media screen and (max-width: 1280px) {
  .metodologia {
    margin: 5rem 0 2rem 5rem;
  }
  .metodologia img {
    width: 70rem;
  }
  .lisa img {
    width: 62rem;
  }
}
@media screen and (max-width: 1024px) {
  .metodologia img {
    width: 60rem;
  }
  .lisa img {
    width: 50rem;
  }
  .text-container {
    margin: 0 2rem;
  }
  h3 {
    font-size: 3.5rem;
  }
  p {
    font-size: 2rem;
  }
  .a {
    position: relative;
    bottom: -15rem;
  }
  .b {
    position: relative;
    bottom: 15rem;
  }
}
@media screen and (max-width: 768px) {
  .metodologia img {
    width: 50rem;
  }
  .lisa img {
    width: 40rem;
  }
  .a {
    position: relative;
    bottom: -5rem;
  }
  .b {
    position: relative;
    bottom: 5rem;
  }
  h3 {
    font-size: 3rem;
  }
  p {
    font-size: 1.8rem;
  }
}
@media screen and (max-width: 576px) {
  .metodologia img {
    width: 40rem;
  }
  .lisa img {
    width: 30rem;
  }
  .a {
    position: relative;
    bottom: 0;
  }
  .b {
    position: relative;
    bottom: 0;
  }
  .metodologia {
    margin: 5rem 0 3rem 2rem;
  }
}
@media screen and (max-width: 540px) {
  h3 {
    font-size: 2.8rem;
  }
  p {
    font-size: 1.6rem;
  }
}
@media screen and (max-width: 480px) {
  .metodologia img {
    width: 35rem;
  }
  .lisa img {
    width: 25rem;
  }
  h3 {
    font-size: 2.6rem;
  }
  p {
    font-size: 1.4rem;
  }
}
@media screen and (max-width: 426px) {
  .metodologia img {
    width: 30rem;
  }
  .lisa img {
    width: 20em;
  }
  h3 {
    font-size: 2.5rem;
  }
  p {
    font-size: 1.3rem;
  }
}
@media screen and (max-width: 376px) {
  .metodologia img {
    width: 25rem;
  }
  .lisa img {
    width: 18em;
  }
  h3 {
    font-size: 2rem;
  }
  p {
    font-size: 1rem;
  }
}
@media screen and (max-width: 320px) {
  .metodologia img {
    width: 23rem;
  }
  .lisa img {
    width: 16em;
  }
  h3 {
    font-size: 1.8rem;
  }
  p {
    font-size: 0.8rem;
  }
}
</style>
