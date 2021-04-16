<template>
  <div>
    <NavigationMX />
    <CardsMX />
    <CardsAlt />
    <Footer />
  </div>
</template>

<script>
import NavigationMX from '@/components/NavigationMX'
import CardsMX from '@/components/CardsMX'
import CardsAlt from '@/components/CardsAlt'
import Footer from '@/components/Footer'
export default {
  components: {
    NavigationMX,
    CardsMX,
    CardsAlt,
    Footer,
  },
}
</script>
