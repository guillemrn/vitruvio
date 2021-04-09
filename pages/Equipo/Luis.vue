<template>
  <div class="team-container">
    <Navigation />
    <nuxt-link to="/españa#team" class="close-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="40"
        height="40"
        fill="#2D2D2D"
        class="bi bi-x-circle-fill"
        viewBox="0 0 16 16"
      >
        <path
          d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM5.354 4.646a.5.5 0 1 0-.708.708L7.293 8l-2.647 2.646a.5.5 0 0 0 .708.708L8 8.707l2.646 2.647a.5.5 0 0 0 .708-.708L8.707 8l2.647-2.646a.5.5 0 0 0-.708-.708L8 7.293 5.354 4.646z"
        />
      </svg>
    </nuxt-link>
    <section class="container">
      <div class="team-bar">
        <figure><img src="@/assets/images/luis.svg" alt="Luis" /></figure>
        <h1 class="name">LUIS ANTONIO A.</h1>
        <p class="puesto">CINEASTA / DIRECTOR CREATIVO</p>
        <p class="description">
          Luis, es un egresado de la Universidad de Guadalajara, con
          licenciatura en Artes Audiovisuales. Ha trabajado como director
          creativo en agencias de publicidad para marcas como: Menú local,
          Erdinger, UNE, Balones Molten, Vimifos, entre otras.
        </p>
        <p class="description">
          Durante su carrera como cineasta ha sido seleccionado en el SHORT FILM
          CORNNER, del festival de Cannes 2020, así como en la selección oficial
          de SHORTS MÉXICO 2020, con su cortometraje ERÓ, el cual recibió el
          premio a mejor guión en categoría de ficción.
        </p>
      </div>
      <div>
        <VueSlickCarousel
          class="carousel-vtrv"
          :arrows="true"
          :dots="false"
          :infinite="true"
          :center-mode="true"
          :center-padding="'20px'"
          :slides-to-show="1"
          :slides-to-scroll="1"
          :variable-width="true"
          :adaptive-height="true"
        >
          <CThemeProvider>
            <div>
              <figure class="carousel-img" m="4" @click="open">
                <img src="@/assets/audiovisual/carousel/1.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
                class="modal-vtrv"
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <figure class="modal-img">
                    <img src="@/assets/audiovisual/1.jpg" alt="" />
                  </figure>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <!-- <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/2.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/2.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/3.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/3.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/4.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/4.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/5.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/5.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/6.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/6.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/7.jpg" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/7.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/8.jpg" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/8.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/9.jpg" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/9.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/10.jpg" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/11.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/12.jpg" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/12.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/13.jpg" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/13.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/14.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/14.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider>
          <CThemeProvider>
            <div>
              <figure class="carousel-img" @click="open">
                <img src="@/assets/audiovisual/carousel/15.png" alt="" />
              </figure>
              <c-modal
                :is-open="isOpen"
                :on-close="close"
                :close-on-overlay-click="false"
                is-centered
              >
                <c-modal-content ref="content">
                  <c-modal-close-button />
                  <c-modal-body>
                    <figure class="modal-img">
                      <img src="@/assets/audiovisual/15.jpg" alt="" />
                    </figure>
                  </c-modal-body>
                </c-modal-content>
                <c-modal-overlay />
              </c-modal>
            </div>
          </CThemeProvider> -->
        </VueSlickCarousel>
      </div>
    </section>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
import {
  CThemeProvider,
  CModal,
  CModalOverlay,
  CModalContent,
  CModalCloseButton,
} from '@chakra-ui/vue'
export default {
  components: {
    Navigation,
    VueSlickCarousel,
    CThemeProvider,
    CModal,
    CModalOverlay,
    CModalContent,
    CModalCloseButton,
  },
  data() {
    return {
      isOpen: false,
    }
  },
  methods: {
    open() {
      this.isOpen = true
    },
    close() {
      this.isOpen = false
    },
  },
}
</script>

<style scoped>
.team-bar {
  background-color: var(--metodologia);
  background-image: url(@/assets/images/logo-mask.svg);
  width: 60rem;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-flow: column;
  padding: 0 3rem;
}
.name {
  font-family: sifonn;
  font-size: 5rem;
  color: #fff;
  text-transform: uppercase;
  margin-top: 1rem;
}
.puesto {
  font-family: c-gothic;
  font-size: 2.6rem;
  color: #212121;
  text-transform: uppercase;
  margin-top: 3.5rem;
}
.description {
  font-family: c-gothic;
  font-size: 1.6rem;
  color: #fff;
  margin-top: 5rem;
}
.close-icon {
  position: absolute;
  right: 0;
  margin: 20px;
}
.carousel-vtrv {
  width: 50%;
  position: absolute;
  top: 80%;
  left: 40%;
}
.carousel-img img {
  width: 20rem;
}
.modal-img img {
  width: 50rem;
}
.modal-vtrv {
  width: 60rem;
}
</style>
