<template>
  <div>
    <Navigation />
    <Hero />
    <Anatomical />
    <Services />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Hero from '@/components/Hero'
import Anatomical from '@/components/Anatomical'
import Services from '@/components/Services'
export default {
  components: {
    Navigation,
    Hero,
    Anatomical,
    Services,
  },
}
</script>
