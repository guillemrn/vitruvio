<template>
  <div>
    <Navigation />
    <Cards />
    <CardsAlt />
    <Footer />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Cards from '@/components/Cards'
import CardsAlt from '@/components/CardsAlt'
import Footer from '@/components/Footer'
export default {
  components: {
    Navigation,
    Cards,
    CardsAlt,
    Footer,
  },
}
</script>
