<template>
  <div id="app">
    <Hero/>
    <Thermostar/>
    <Advantages/>
    <Functions/>
    <Gallery/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Thermostar from './components/Thermostar.vue'
import Advantages from './components/Advantages.vue'
import Functions from './components/Functions.vue'
import Gallery from './components/Gallery.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Hero,
    Thermostar,
    Advantages,
    Functions,
    Gallery,
    Contact,
    Footer,
  }
}
</script>
<style lang="scss">
  @import "./assets/sass/app.scss";
</style>



