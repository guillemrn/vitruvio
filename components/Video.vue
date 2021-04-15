<template>
  <div id="quienesSomos" class="videoContainer">
    <iframe
      src="https://www.youtube.com/embed/g6UVUvL96rE"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
      rel="0"
      showinfo="0"
    ></iframe>
  </div>
</template>

<style scoped>
.videoContainer {
  text-align: center;
  width: 100%;
  height: 100vh;
  background-color: var(--metodologia);
  display: flex;
  align-items: center;
  justify-content: center;
}
.videoContainer iframe {
  border-radius: 2rem;
  width: 100rem;
  height: 60rem;
}

/* -------------------------------------------Responsive design */

@media screen and (max-width: 1536px) {
}
@media screen and (max-width: 1440px) {
}
@media screen and (max-width: 1280px) {
  .videoContainer iframe {
    width: 80rem;
    height: 50rem;
  }
}
@media screen and (max-width: 1024px) {
  .videoContainer iframe {
    width: 70rem;
    height: 50rem;
  }
}
@media screen and (max-width: 768px) {
  .videoContainer iframe {
    width: 50rem;
    height: 30rem;
    border-radius: 1rem;
  }
}
@media screen and (max-width: 576px) {
  .videoContainer iframe {
    width: 50rem;
    height: 30rem;
  }
}
@media screen and (max-width: 540px) {
}
@media screen and (max-width: 480px) {
  .videoContainer iframe {
    width: 40rem;
    height: 25rem;
  }
}
@media screen and (max-width: 426px) {
  .videoContainer iframe {
    width: 38rem;
    height: 22rem;
  }
}
@media screen and (max-width: 376px) {
  .videoContainer iframe {
    width: 30rem;
    height: 20rem;
  }
}
@media screen and (max-width: 320px) {
  .videoContainer iframe {
    width: 28rem;
    height: 18rem;
  }
}
</style>
