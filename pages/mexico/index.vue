<template>
  <div>
    <Navigation />
    <Hero />
    <Anatomical />
    <Services />
    <Metodologia />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Hero from '@/components/Hero'
import Anatomical from '@/components/Anatomical'
import Services from '@/components/Services'
import Metodologia from '@/components/Metodologia'
export default {
  components: {
    Navigation,
    Hero,
    Anatomical,
    Services,
    Metodologia,
  },
}
</script>
