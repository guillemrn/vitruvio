<template>
  <section id="conocenos">
    <figure class="img-man">
      <img src="@/assets/images/man.png" alt="man" />
    </figure>
    <div>
      <h2>Bajo el concepto de<br /><span>Anatomical marketing</span></h2>
      <figure class="mobile-img">
        <img src="@/assets/images/mobile-man.png" alt="man" />
      </figure>
      <p>Trabajamos bajo las reglas estéticas de la experiencia humana.</p>
      <p>
        Cuando juzgamos que algo es
        <strong>BELLO, FEO, SUBLIME O ELEGANTE,</strong> estamos haciendo
        juicios estéticos, basados en la
        <strong>anatomía física y conceptual</strong>
        de las cosas.
      </p>
      <p>
        Analizar y definir la <strong>ANATOMÍA DE TU MARCA,</strong> nos permite
        ser realmente efectivos al momento de querer mostrarla.
        <strong>Observarla, medirla y diseccionarla,</strong> hace posible
        generar poderosos conceptos de comunicación, que atraigan la atención e
        interés del cliente, orientando su decisión de compra a favor de tu
        servicio o producto.
      </p>
    </div>
  </section>
</template>

<style scoped>
section {
  background-color: var(--yellow);
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 100%;
}
h2 {
  font-family: sifonn;
  font-size: 2.8rem;
  text-transform: uppercase;
  text-align: center;
}
span {
  font-size: 5.3rem;
  letter-spacing: -1px;
}
p {
  font-family: c-gothic;
  font-size: 2.6rem;
  margin: 4rem 0;
  padding: 0 14rem;
  letter-spacing: 1px;
  text-align: justify;
}
strong {
  font-family: b-gothic;
  font-weight: bold;
}
.mobile-img {
  display: none;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  p {
    margin: 4rem 0;
    padding: 0 6rem;
    font-size: 2.4rem;
  }
  figure img {
    width: 85rem;
  }
  h2 {
    font-size: 2.4rem;
  }
  span {
    font-size: 4.3rem;
  }
}
@media screen and (max-width: 1440px) {
  p {
    margin: 3rem 0;
    padding: 0 4rem;
    font-size: 2.2rem;
  }
  h2 {
    font-size: 2.2rem;
  }
  span {
    font-size: 4rem;
  }
  figure img {
    width: 82rem;
  }
}
@media screen and (max-width: 1280px) {
  p {
    margin: 3rem 0;
    padding: 0 3rem;
    font-size: 1.9rem;
  }
  h2 {
    font-size: 1.9rem;
  }
  span {
    font-size: 3.2rem;
  }
  figure img {
    width: 78rem;
  }
}
@media screen and (max-width: 1024px) {
  p {
    margin: 2rem 0;
    padding: 0 2rem;
    font-size: 1.7rem;
  }
  h2 {
    font-size: 1.7rem;
  }
  span {
    font-size: 3rem;
  }
  figure img {
    width: 58rem;
  }
}
@media screen and (max-width: 768px) {
  .img-man {
    display: none;
  }
  .mobile-img {
    display: initial;
  }
  .mobile-img img {
    margin: 3rem 0;
  }
  #conocenos {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    text-align: center;
    padding: 6rem 0;
  }
  p {
    text-align: center;
  }
}
@media screen and (max-width: 576px) {
  .mobile-img img {
    width: 48rem;
  }
  p {
    font-size: 1.6rem;
  }
}
@media screen and (max-width: 540px) {
  .mobile-img img {
    width: 45rem;
  }
}
@media screen and (max-width: 480px) {
  .mobile-img img {
    width: 42rem;
  }
  p {
    font-size: 1.5rem;
  }
}
@media screen and (max-width: 426px) {
  h2 {
    font-size: 1.5rem;
  }
  span {
    font-size: 2.5rem;
  }
  .mobile-img img {
    width: 38rem;
  }
  p {
    padding: 0 1rem;
  }
}
@media screen and (max-width: 376px) {
  .mobile-img img {
    width: 30rem;
  }
  p {
    font-size: 1.4rem;
  }
}
@media screen and (max-width: 320px) {
  h2 {
    font-size: 1.4rem;
  }
  span {
    font-size: 2.2rem;
  }
  .mobile-img img {
    width: 25rem;
  }
  p {
    font-size: 1.2rem;
  }
}
</style>
