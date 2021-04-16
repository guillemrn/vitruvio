<template>
  <!-- <header class="header">
    <nuxt-link to="/">
      <figure class="logo">
        <img src="@/assets/images/logo.png" alt="Logo vitruvio" />
      </figure>
    </nuxt-link>
    <nav class="nav">
      <nuxt-link to="/españa" class="link">Inicio</nuxt-link>
      <nuxt-link to="/españa#conocenos" class="link">Conócenos</nuxt-link>
      <nuxt-link to="/españa#servicios" class="link">Servicios</nuxt-link>
      <nuxt-link to="/españa#team" class="link">Equipo</nuxt-link>
      <nuxt-link to="/españa#metodologia" class="link">Metodología</nuxt-link>
      <nuxt-link to="/paquetes" class="link">Paquetes</nuxt-link>
      <a href="#" class="link">Blog</a>
      <nuxt-link to="/contacto" class="link">Contacto</nuxt-link>
    </nav>
  </header> -->
  <section id="header" class="nav-1">
    <nuxt-link to="/">
      <figure class="logo">
        <img src="@/assets/images/logo.png" alt="Logo vitruvio" />
      </figure>
    </nuxt-link>
    <input id="menu-btn" class="menu-btn" type="checkbox" />
    <label class="menu-icon" for="menu-btn"
      ><span class="navicon"></span
    ></label>
    <ul class="menu">
      <li><nuxt-link to="/españa" class="link">Inicio</nuxt-link></li>
      <li>
        <nuxt-link to="/españa#conocenos" class="link">Conócenos</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/españa#servicios" class="link">Servicios</nuxt-link>
      </li>
      <li><nuxt-link to="/españa#team" class="link">Equipo</nuxt-link></li>
      <li>
        <nuxt-link to="/españa#metodologia" class="link">Metodología</nuxt-link>
      </li>
      <li><nuxt-link to="/paquetes" class="link">Paquetes</nuxt-link></li>
      <li><a href="#" class="link">Blog</a></li>
      <li><nuxt-link to="/contacto" class="link">Contacto</nuxt-link></li>
    </ul>
  </section>
</template>

<style scoped>
/* .header {
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
} */
.link {
  color: #fff;
}

/* header */

.nav-1 {
  position: relative;
  z-index: 3;
  background-color: var(--nav-text);
  height: 9rem;
}

.nav-1 ul {
  margin: 0;
  padding: 0;
  list-style: none;
  overflow: hidden;
  background-color: var(--nav-text);
}

.nav-1 li .link {
  display: block;
  padding: 10px 10px;
  border-right: none;
  text-decoration: none;
}

.link {
  transition: 300ms;
  font-family: sifonn;
  text-transform: uppercase;
  font-size: 2rem;
}

.nav-1 .link:hover {
  color: var(--metodologia);
}

.nav-1 .logo {
  display: block;
  float: left;
  font-size: 2em;
  padding: 10px 20px;
  text-decoration: none;
}

/* menu */

.nav-1 .menu {
  clear: both;
  max-height: 0;
  transition: max-height 0.2s ease-out;
  margin-top: 1rem;
}

/* menu icon */

.nav-1 .menu-icon {
  cursor: pointer;
  display: inline-block;
  float: right;
  padding: 28px 20px;
  position: relative;
  user-select: none;
}

.nav-1 .menu-icon .navicon {
  background: #fff;
  display: block;
  height: 2px;
  position: relative;
  transition: background 0.2s ease-out;
  width: 18px;
}

.nav-1 .menu-icon .navicon:before,
.nav-1 .menu-icon .navicon:after {
  background: #fff;
  content: '';
  display: block;
  height: 100%;
  position: absolute;
  transition: all 0.2s ease-out;
  width: 100%;
}

.nav-1 .menu-icon .navicon:before {
  top: 5px;
}

.nav-1 .menu-icon .navicon:after {
  top: -5px;
}

/* menu btn */

.nav-1 .menu-btn {
  display: none;
}

.nav-1 .menu-btn:checked ~ .menu {
  max-height: 400px;
}

.nav-1 .menu-btn:checked ~ .menu-icon .navicon {
  background: transparent;
}

.nav-1 .menu-btn:checked ~ .menu-icon .navicon:before {
  transform: rotate(-45deg);
}

.nav-1 .menu-btn:checked ~ .menu-icon .navicon:after {
  transform: rotate(45deg);
}

.nav-1 .menu-btn:checked ~ .menu-icon:not(.steps) .navicon:before,
.nav-1 .menu-btn:checked ~ .menu-icon:not(.steps) .navicon:after {
  top: 0;
}

/* 48em = 768px */

@media screen and (min-width: 769px) {
  .nav-1 li {
    float: left;
  }
  .nav-1 li .link {
    padding: 20px 20px;
  }
  .nav-1 .menu {
    clear: none;
    float: right;
    max-height: none;
  }
  .nav-1 .menu-icon {
    display: none;
  }
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .logo img {
    width: 20rem;
  }
}
@media screen and (max-width: 1440px) {
}
@media screen and (max-width: 1366px) {
  .link {
    font-size: 1.6rem;
  }
}
@media screen and (max-width: 1280px) {
  .logo img {
    width: 19rem;
  }
}
@media screen and (max-width: 1024px) {
  .logo img {
    width: 18rem;
  }
  .link {
    font-size: 1.1rem;
  }
}
@media screen and (max-width: 768px) {
}
@media screen and (max-width: 576px) {
  .logo img {
    width: 18rem;
  }
}
@media screen and (max-width: 540px) {
  .logo img {
    width: 16rem;
  }
}
@media screen and (max-width: 480px) {
  .logo img {
    width: 15rem;
  }
}
@media screen and (max-width: 426px) {
  .logo img {
    width: 14rem;
  }
}
@media screen and (max-width: 376px) {
  .logo img {
    width: 12rem;
  }
}
@media screen and (max-width: 320px) {
  .logo img {
    width: 10rem;
  }
}
</style>
