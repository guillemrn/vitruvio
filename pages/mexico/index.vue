<template>
  <div>
    <NavigationMX />
    <Hero />
    <Anatomical />
    <Video />
    <Services />
    <Team />
    <Metodologia />
    <Footer />
  </div>
</template>

<script>
import NavigationMX from '@/components/NavigationMX'
import Hero from '@/components/Hero'
import Anatomical from '@/components/Anatomical'
import Video from '@/components/Video'
import Services from '@/components/Services'
import Team from '@/components/Team'
import Metodologia from '@/components/Metodologia'
import Footer from '@/components/Footer'
export default {
  components: {
    NavigationMX,
    Hero,
    Anatomical,
    Video,
    Services,
    Team,
    Metodologia,
    Footer,
  },
}
</script>
