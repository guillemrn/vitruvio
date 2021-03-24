<template>
  <header class="header">
    <figure class="logo">
      <img src="@/assets/images/logo.svg" alt="Logo vitruvio" />
    </figure>
    <nav class="nav">
      <a href="#">Inicio</a>
      <a href="#">Conócenos</a>
      <a href="#">Servicios</a>
      <a href="#">Equipo</a>
      <a href="#">Metodología</a>
      <a href="#">Paquetes</a>
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
.nav a {
  font-family: siffon;
}
</style>
