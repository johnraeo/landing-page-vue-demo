<script>
import Navbar from '../landing/Navbar.vue'
import Header from '../landing/Header.vue'
import Section1 from '../landing/Section1.vue'
import Section2 from '../landing/Section2.vue'
import Section3 from '../landing/Section3.vue'
import Footer from '../landing/Footer.vue'

export default {
  name: 'Landing',
  components: {
    Navbar,
    Header,
    Section1,
    Section2,
    Section3,
    Footer
  }
}
</script>

<template>
  <Navbar />
  <Header />
  <Section1 />
  <Section2 />
  <Section3 />
  <Footer />
</template>

<style scoped>

</style>