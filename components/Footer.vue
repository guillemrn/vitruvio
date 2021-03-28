<template>
  <footer class="footer">
    <h3>¡QUEREMOS SABER DE TI!</h3>
    <figure class="social">
      <a href="#"><img src="@/assets/images/facebook.svg" alt="facebook" /></a>
      <a href="#"
        ><img src="@/assets/images/instagram.svg" alt="instagram"
      /></a>
    </figure>
    <div class="links-container">
      <figure>
        <img src="@/assets/images/logo.svg" alt="logo" />
      </figure>
      <a href="#" class="links">
        DIRECCIÓN:<br />Parque de las estrellas 2874, Guadalajara, Jalisco,
        México.
      </a>
      <a href="tel:" class="links">TELÉFONO: +52 (33) 333.4800.728</a>
      <a href="#" class="links">CORREO: vitruvio.mkt@gmail.com</a>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: var(--footer);
  color: #fff;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  align-items: center;
  height: 40vh;
  grid-gap: 2rem;
  padding: 0 4rem;
}
h3 {
  font-family: sifonn;
  font-size: 3.8rem;
  padding: 0 10rem;
  text-align: center;
}
.social img {
  margin: 2rem;
}
.links-container {
  display: flex;
  align-content: center;
  justify-content: center;
  flex-flow: column;
}
.links {
  font-family: c-gothic;
  font-size: 2.4rem;
  text-decoration: none;
  color: #fff;
  margin: 1rem 0;
  transition: 300ms;
}
.links:hover {
  color: var(--metodologia);
}
</style>
