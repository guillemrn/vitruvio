<template>
  <footer class="footer">
    <h3>¡QUEREMOS SABER DE TI!</h3>
    <figure class="social">
      <a href="https://www.facebook.com/vitruvio.mkt" target="_blank"
        ><img src="@/assets/images/facebook.png" alt="facebook"
      /></a>
      <a href="https://www.instagram.com/vitruvio.mkt/" target="_blank"
        ><img src="@/assets/images/instagram.png" alt="instagram"
      /></a>
    </figure>
    <div class="links-container">
      <figure>
        <img src="@/assets/images/logo.png" alt="logo" />
      </figure>
      <a href="#" class="links">
        DIRECCIÓN:<br />Parque de las estrellas 2874, Guadalajara, Jalisco,
        México.
      </a>
      <a href="tel:523329700751" class="links">TELÉFONO: +52 (33) 297.007.51</a>
      <a href="mailto:vitruvio.mkt@gmail.com" class="links"
        >CORREO: vitruvio.mkt@gmail.com</a
      >
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

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
}
@media screen and (max-width: 1440px) {
  h3 {
    padding: 0 8rem;
  }
}
@media screen and (max-width: 1366px) {
  h3 {
    padding: 0 6rem;
    font-size: 3rem;
  }
  .social img {
    width: 28rem;
  }
  .links-container img {
    width: 24rem;
  }
  .links {
    font-size: 2rem;
  }
}
@media screen and (max-width: 1280px) {
  h3 {
    padding: 0 6rem;
  }
}
@media screen and (max-width: 1024px) {
  h3 {
    padding: 0 4rem;
    font-size: 3rem;
  }
  .social img {
    width: 24rem;
  }
  .links-container img {
    width: 20rem;
  }
  .links {
    font-size: 1.8rem;
  }
}
@media screen and (max-width: 768px) {
  .footer {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    height: 100%;
    text-align: center;
    padding: 4rem 0;
  }
  h3 {
    font-size: 3.8rem;
  }
  .social img {
    width: 24rem;
  }
  .links-container img {
    width: 24rem;
  }
  .links {
    font-size: 2rem;
    margin-top: 2rem;
  }
}
@media screen and (max-width: 576px) {
  h3 {
    font-size: 3.4rem;
  }
  .social img {
    width: 20rem;
  }
  .links {
    font-size: 1.8rem;
  }
}
@media screen and (max-width: 540px) {
  .links {
    font-size: 1.7rem;
  }
}
@media screen and (max-width: 480px) {
  h3 {
    font-size: 3rem;
  }
  .social img {
    width: 18rem;
    margin: 1rem;
  }
  .links-container img {
    width: 20rem;
  }
  .links {
    font-size: 1.6rem;
    margin-top: 1rem;
  }
}
@media screen and (max-width: 426px) {
  h3 {
    font-size: 2.5rem;
  }
  .social img {
    width: 17rem;
  }
  .links-container img {
    width: 18rem;
  }
  .links {
    font-size: 1.5rem;
    padding: 0 2rem;
  }
}
@media screen and (max-width: 376px) {
  h3 {
    font-size: 2.2rem;
  }
  .social img {
    width: 15rem;
  }
  .links-container img {
    width: 16rem;
  }
  .links {
    font-size: 1.4rem;
  }
}
@media screen and (max-width: 320px) {
  h3 {
    font-size: 1.8rem;
  }
  .social img {
    width: 12rem;
  }
  .links-container img {
    width: 15rem;
  }
}
</style>
