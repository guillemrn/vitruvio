<template>
  <section class="team-container">
    <figure class="team-img">
      <img src="@/assets/images/team.svg" alt="Team" />
    </figure>
    <div class="team">
      <nuxt-link to="/Equipo/Luis" class="item">
        <figure><img src="@/assets/images/luis.svg" alt="Luis" /></figure>
        <h3>LUIS ANTONIO A.</h3>
        <p>CINEASTA</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Enrique" class="item">
        <figure><img src="@/assets/images/enrique.svg" alt="Enrique" /></figure>
        <h3>ENRIQUE R.</h3>
        <p>DIRECTOR DE ARTE</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Hugo" class="item">
        <figure><img src="@/assets/images/hugo.svg" alt="Hugo" /></figure>
        <h3>hugo v.</h3>
        <p>MERCADÓLOGO</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Victoria" class="item">
        <figure>
          <img src="@/assets/images/victoria.svg" alt="Victoria" />
        </figure>
        <h3>VICTORIA A.</h3>
        <p>ANIMADORA DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Kenji" class="item">
        <figure><img src="@/assets/images/kenji.svg" alt="Kenji" /></figure>
        <h3>KENJI K.</h3>
        <p>MUSICALIZADOR</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Diana" class="item">
        <figure><img src="@/assets/images/diana.svg" alt="Diana" /></figure>
        <h3>diana t.</h3>
        <p>FOTOGRÁFA</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Nelly" class="item">
        <figure><img src="@/assets/images/nelly.svg" alt="Nelly" /></figure>
        <h3>nelly s.</h3>
        <p>ESTRÁTEGA DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Nelly" class="item">
        <figure><img src="@/assets/images/nelly.svg" alt="Nelly" /></figure>
        <h3>nelly s.</h3>
        <p>ESTRÁTEGA DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Nelly" class="item">
        <figure><img src="@/assets/images/nelly.svg" alt="Nelly" /></figure>
        <h3>nelly s.</h3>
        <p>ESTRÁTEGA DIGITAL</p>
      </nuxt-link>
    </div>
  </section>
</template>

<style scoped>
.team-container {
  background-color: var(--yellow-team);
}
.team-img img {
  margin: 15rem 10rem 10rem;
}
.team {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 2rem;
  text-align: center;
}
.item {
  margin: 4rem;
  text-decoration: none;
  color: var(--text-grid);
}
.item h3 {
  font-family: sifonn;
  font-size: 2.7rem;
  margin: 2.5rem 0 1.8rem 0;
  text-transform: uppercase;
}
.item p {
  font-family: c-gothic;
  font-size: 1.8rem;
  text-transform: uppercase;
}
</style>
