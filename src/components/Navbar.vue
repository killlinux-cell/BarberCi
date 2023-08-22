<template>
  <nav class="navbar">
    <div class="container">
      <div class="logo">Momo Coiffeur</div>
       <button @click="toggleMenu" class="hamburger">&#9776;</button>
      <ul :class="{ 'nav-links': true, 'open': isMenuOpen }">
        <li><a href="#hero">Accueil</a></li>
        <li><a href="#gallerie">Galerie</a></li>
        <li><a href="#about">À Propos</a></li>
        <li><a href="#visite">Contact</a></li>
      </ul>

    </div>
  </nav>
</template>

<script>

export default{

    
    name: 'Navbar',
    data() {
    return {
      isMenuOpen: false
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }

}
</script>

<style>
@import '../assets/navbar.css';
</style>
