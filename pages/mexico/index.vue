<template>
  <div>
    <NavigationMX />
    <Hero />
    <Up />
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
import Up from '@/components/Up'
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
    Up,
    Anatomical,
    Video,
    Services,
    Team,
    Metodologia,
    Footer,
  },
}
</script>
