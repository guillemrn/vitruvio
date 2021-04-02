<template>
  <header class="header">
    <nuxt-link to="/">
      <figure class="logo">
        <img src="@/assets/images/logo.svg" alt="Logo vitruvio" />
      </figure>
    </nuxt-link>
    <nav class="nav">
      <a href="#">Inicio</a>
      <a href="#conocenos">Conócenos</a>
      <a href="#">Servicios</a>
      <a href="#">Equipo</a>
      <a href="#">Metodología</a>
      <a href="#">Paquetes</a>
      <a href="#">Blog</a>
      <a href="#">Contacto</a>
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
</style>
