<template>
  <div>
    <Navigation />
    <Hero />
    <Anatomical />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Hero from '@/components/Hero'
import Anatomical from '@/components/Anatomical'
export default {
  components: {
    Navigation,
    Hero,
    Anatomical,
  },
}
</script>
