<template>
  <Navbar></Navbar>
  <Hero></Hero>
  <About></About>
  <Gallerie></Gallerie>
  <Visite></Visite>
  <Footer></Footer>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Gallerie from './components/Gallerie.vue';
import About from './components/About.vue';
import Visite from './components/Visite.vue';
import Footer from './components/Footer.vue';

export default{
  name: 'App',
  components:{
    Navbar,
    Hero,
    Gallerie,
    About,
    Footer,
    Visite,
  }
}
</script>

<style scoped>
</style>
