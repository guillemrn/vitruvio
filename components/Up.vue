<template>
  <figure class="cta-whatsapp">
    <a href="#header"><img src="@/assets/images/up.svg" alt="up" /></a>
  </figure>
</template>

<style scoped>
.cta-whatsapp {
  position: fixed;
  top: 85%;
  right: 0;
  display: flex;
  align-items: center;
  z-index: 100;
}
.cta-whatsapp img {
  width: 8rem;
  padding-right: 2rem;
  margin-left: 4rem;
}
a {
  text-decoration: none;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
  .cta-whatsapp img {
    width: 7.5rem;
  }
}
@media screen and (max-width: 1440px) {
  .cta-whatsapp img {
    width: 7rem;
  }
}
@media screen and (max-width: 1280px) {
  .cta-whatsapp img {
    width: 6.5rem;
  }
}
@media screen and (max-width: 1024px) {
  .cta-whatsapp img {
    width: 6rem;
  }
}

@media screen and (max-width: 768px) {
  .cta-whatsapp img {
    width: 6rem;
  }
}
@media screen and (max-width: 426px) {
  .cta-whatsapp img {
    width: 5.5rem;
  }
}
@media screen and (max-width: 376px) {
  .cta-whatsapp img {
    width: 5rem;
  }
}
@media screen and (max-width: 320px) {
}
</style>
