<template>
  <div>
    <Navigation />
    <Hero />
    <Anatomical />
    <Services />
    <Metodologia />
    <Footer />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Hero from '@/components/Hero'
import Anatomical from '@/components/Anatomical'
import Services from '@/components/Services'
import Metodologia from '@/components/Metodologia'
import Footer from '@/components/Footer'
export default {
  components: {
    Navigation,
    Hero,
    Anatomical,
    Services,
    Metodologia,
    Footer,
  },
}
</script>
