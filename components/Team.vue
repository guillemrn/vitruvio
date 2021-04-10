<template>
  <section id="team" class="team-container">
    <figure class="team-img">
      <img src="@/assets/images/team.png" alt="Team" />
    </figure>
    <div class="team">
      <nuxt-link to="/Equipo/Luis" class="item">
        <figure><img src="@/assets/images/luis.png" alt="Luis" /></figure>
        <h3>LUIS ANTONIO A.</h3>
        <p>CINEASTA</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Enrique" class="item">
        <figure><img src="@/assets/images/enrique.png" alt="Enrique" /></figure>
        <h3>ENRIQUE R.</h3>
        <p>DIRECTOR DE ARTE</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Hugo" class="item">
        <figure><img src="@/assets/images/hugo.png" alt="Hugo" /></figure>
        <h3>hugo v.</h3>
        <p>MERCADÓLOGO</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Victoria" class="item">
        <figure>
          <img src="@/assets/images/andres.png" alt="Andrés" />
        </figure>
        <h3>ANDRÉS V.</h3>
        <p>ANIMADOR DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Kenji" class="item">
        <figure><img src="@/assets/images/kenji.png" alt="Kenji" /></figure>
        <h3>KENJI K.</h3>
        <p>MUSICALIZADOR</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Diana" class="item">
        <figure><img src="@/assets/images/diana.png" alt="Diana" /></figure>
        <h3>diana t.</h3>
        <p>FOTÓGRAFA</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Nelly" class="item">
        <figure><img src="@/assets/images/nayelhi.png" alt="Nayelhi" /></figure>
        <h3>NAYELHI D.</h3>
        <p>ESTRÁTEGA DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Nelly" class="item">
        <figure><img src="@/assets/images/isaac.png" alt="Isaac" /></figure>
        <h3>ISAAC R.</h3>
        <p>ESPECIALISTA EN DATA</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Nelly" class="item">
        <figure>
          <img src="@/assets/images/gioconda.png" alt="Gioconda" />
        </figure>
        <h3>GIOCONDA L.</h3>
        <p>ATENCIÓN A CLIENTES</p>
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
