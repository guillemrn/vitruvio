<template>
  <section id="team" class="team-container">
    <figure class="team-img">
      <img src="https://i.imgur.com/0oWNhHX.png" alt="Team" />
    </figure>
    <div class="team">
      <nuxt-link to="/Equipo/Luis" class="item">
        <figure>
          <img src="https://i.imgur.com/Sa7jGgz.png" alt="Luis" />
        </figure>
        <h3>LUIS ANTONIO A.</h3>
        <p>CINEASTA</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Enrique" class="item">
        <figure>
          <img src="https://i.imgur.com/VRKfHyK.png" alt="Enrique" />
        </figure>
        <h3>ENRIQUE R.</h3>
        <p>DIRECTOR DE ARTE</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Hugo" class="item">
        <figure>
          <img src="https://i.imgur.com/G1xKi1b.png" alt="Hugo" />
        </figure>
        <h3>hugo v.</h3>
        <p>MERCADÓLOGO</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Andres" class="item">
        <figure>
          <img src="https://i.imgur.com/W2OP5mY.png" alt="Andrés" />
        </figure>
        <h3>ANDRÉS V.</h3>
        <p>ANIMADOR DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Kenji" class="item">
        <figure>
          <img src="https://i.imgur.com/jsmb3IP.png" alt="Kenji" />
        </figure>
        <h3>KENJI K.</h3>
        <p>compositor</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Diana" class="item">
        <figure>
          <img src="https://i.imgur.com/TgatKJ9.png" alt="Diana" />
        </figure>
        <h3>diana t.</h3>
        <p>FOTÓGRAFA</p>
      </nuxt-link>
    </div>
    <div class="last-items">
      <nuxt-link to="/Equipo/Nayelhi" class="last-item">
        <figure>
          <img src="https://i.imgur.com/69px3yd.png" alt="Nayelhi" />
        </figure>
        <h3>NAYELHI D.</h3>
        <p>ESTRATEGA DIGITAL</p>
      </nuxt-link>
      <nuxt-link to="/Equipo/Isaac" class="last-item">
        <figure>
          <img src="https://i.imgur.com/wPjL4KP.png" alt="Isaac" />
        </figure>
        <h3>ISAAC R.</h3>
        <p>ESPECIALISTA EN DATA</p>
      </nuxt-link>
    </div>
  </section>
</template>

<style scoped>
.team-container {
  background-color: var(--yellow-team);
}
.team-img img {
  margin: 12rem 8rem 8rem;
  width: 60rem;
}
.team {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 2rem;
  text-align: center;
}
.team img {
  width: 35rem;
}
.last-items img {
  width: 35rem;
}
.item,
.last-item {
  margin: 4rem;
  text-decoration: none;
  color: var(--text-grid);
}
h3 {
  font-family: sifonn;
  font-size: 3rem;
  margin: 2.5rem 0 1.8rem 0;
  text-transform: uppercase;
}
p {
  font-family: c-gothic;
  font-size: 2.5rem;
  text-transform: uppercase;
}
.last-items {
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.last-item {
  margin: 5rem 12rem;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
}
@media screen and (max-width: 1440px) {
  .team img {
    width: 32rem;
  }
  .last-items img {
    width: 32rem;
  }
  h3 {
    font-size: 2.8rem;
    margin: 2rem 0 1.5rem 0;
  }
  p {
    font-size: 2.2rem;
  }
  .team-img img {
    margin: 10rem 6rem 6rem;
    width: 50rem;
  }
}
@media screen and (max-width: 1280px) {
  .last-item {
    margin: 5rem 8rem;
  }
}
@media screen and (max-width: 1200px) {
  .team {
    grid-template-columns: repeat(2, 1fr);
  }
}
@media screen and (max-width: 1024px) {
  .team img {
    width: 25rem;
  }
  .last-items img {
    width: 25rem;
  }
  h3 {
    font-size: 2.5rem;
    margin: 2rem 0 1.5rem 0;
  }
  p {
    font-size: 2rem;
  }
  .team-img img {
    margin: 9rem 5rem 5rem;
    width: 45rem;
  }
}
@media screen and (max-width: 1000px) {
  .team {
    grid-template-columns: repeat(2, 1fr);
  }
}
@media screen and (max-width: 768px) {
  .team {
    grid-template-columns: repeat(2, 1fr);
  }
  .team-img img {
    margin: 8rem 4rem 4rem;
    width: 40rem;
  }
  .team img {
    width: 28rem;
  }
  .last-items img {
    width: 28rem;
  }
  .last-item {
    margin: 5rem 5rem;
  }
}
@media screen and (max-width: 700px) {
  .team {
    grid-template-columns: repeat(1, 1fr);
  }
}
@media screen and (max-width: 576px) {
  .team {
    grid-template-columns: repeat(1, 1fr);
  }
  .team img {
    width: 32rem;
  }
  .last-items img {
    width: 32rem;
  }
  .team-img img {
    margin: 8rem 4rem 4rem;
    width: 35rem;
  }
  .last-items {
    flex-flow: column;
  }
}
@media screen and (max-width: 540px) {
}
@media screen and (max-width: 480px) {
  .team-img img {
    margin: 6rem 3rem 3rem;
    width: 30rem;
  }
  .team img {
    width: 30rem;
  }
  .last-items img {
    width: 30rem;
  }
}
@media screen and (max-width: 426px) {
}
@media screen and (max-width: 376px) {
  .team-img img {
    margin: 4rem 2rem 2rem;
    width: 25rem;
  }
  .team img {
    width: 25rem;
  }
  .last-items img {
    width: 25rem;
  }
  h3 {
    font-size: 2.2rem;
  }
  p {
    font-size: 1.8rem;
  }
}
@media screen and (max-width: 320px) {
  .team-img img {
    width: 20rem;
  }
  .team img {
    width: 20rem;
  }
  .last-items img {
    width: 20rem;
  }
}
</style>
