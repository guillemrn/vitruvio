<template>
  <header class="header">
    <nuxt-link to="/">
      <figure class="logo">
        <img src="@/assets/images/logo.png" alt="Logo vitruvio" />
      </figure>
    </nuxt-link>
    <nav class="nav">
      <a href="#">Inicio</a>
      <a href="#conocenos">Conócenos</a>
      <a href="#servicios">Servicios</a>
      <a href="#team">Equipo</a>
      <a href="#metodologia">Metodología</a>
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
</style>
