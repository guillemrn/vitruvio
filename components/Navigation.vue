<template>
  <header class="header">
    <nuxt-link to="/">
      <figure class="logo">
        <img src="@/assets/images/logo.png" alt="Logo vitruvio" />
      </figure>
    </nuxt-link>
    <nav class="nav">
      <nuxt-link to="/españa">Inicio</nuxt-link>
      <nuxt-link to="/españa#conocenos">Conócenos</nuxt-link>
      <nuxt-link to="/españa#servicios">Servicios</nuxt-link>
      <nuxt-link to="/españa#team">Equipo</nuxt-link>
      <nuxt-link to="/españa#metodologia">Metodología</nuxt-link>
      <nuxt-link to="/paquetes">Paquetes</nuxt-link>
      <a href="#">Blog</a>
      <nuxt-link to="/contacto">Contacto</nuxt-link>
    </nav>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: var(--nav-text);
  height: 9rem;
}
.logo img {
  margin: 2rem 2.5rem;
}
.nav a {
  font-family: sifonn;
  font-size: 2.6rem;
  text-decoration: none;
  color: #fff;
  margin: 0 2.5rem;
  transition: 300ms;
  text-transform: uppercase;
}
.nav a:hover {
  color: var(--metodologia);
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .nav a {
    font-size: 2.4rem;
    margin: 0 1rem;
  }
  .logo img {
    width: 20rem;
  }
}
@media screen and (max-width: 1440px) {
  .nav a {
    font-size: 2.2rem;
  }
}
@media screen and (max-width: 1280px) {
  .nav a {
    font-size: 1.8rem;
  }
  .logo img {
    width: 19rem;
  }
}
@media screen and (max-width: 1024px) {
  .nav a {
    font-size: 1.5rem;
    margin: 0 0.4rem;
  }
  .logo img {
    width: 18rem;
  }
}
@media screen and (max-width: 768px) {
  .nav {
    display: none;
  }
}
@media screen and (max-width: 576px) {
}
@media screen and (max-width: 540px) {
}
@media screen and (max-width: 480px) {
}
@media screen and (max-width: 426px) {
}
@media screen and (max-width: 376px) {
}
@media screen and (max-width: 320px) {
}
</style>
