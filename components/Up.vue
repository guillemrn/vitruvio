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
  width: 10rem;
  padding-right: 2rem;
  margin-left: 4rem;
}
a {
  text-decoration: none;
}

@media screen and (max-width: 768px) {
  .cta-whatsapp img {
    width: 8rem;
  }
}
@media screen and (max-width: 426px) {
  .cta-whatsapp img {
    width: 7rem;
  }
}
</style>
