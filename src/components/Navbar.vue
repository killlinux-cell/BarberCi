<template>
  <nav class="navbar">
    <div class="container">
      <div class="logo">Salon de Coiffure</div>
<!--       <ul class="nav-links">
        <li><a href="#">Accueil</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Galerie</a></li>
        <li><a href="#">À Propos</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
 -->

       <button @click="toggleMenu" class="hamburger">&#9776;</button>
      <ul :class="{ 'nav-links': true, 'open': isMenuOpen }">
        <li><a href="#hero">Accueil</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#gallerie">Galerie</a></li>
        <li><a href="#">À Propos</a></li>
        <li><a href="#visit">Contact</a></li>
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

<style scoped>
/* .navbar {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links li a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-links li a:hover {
  color: #f2a154;
}
 */

 .navbar {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.hamburger {
  display: none;
  background: none;
  border: none;
  font-size: 1.5rem;
  color: #fff;
  cursor: pointer;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
  align-items: center;
}

.nav-links li a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-links li a:hover {
  color: #f2a154;
}

.open {
  display: flex;
  flex-direction: column;
  position: absolute;
  top: 60px;
  right: 0;
  background-color: #222;
  width: 100%;
  z-index: 100;
  padding: 10px 0;
}

@media screen and (max-width: 925px) {
  .hamburger {
    display: block;
  }

  .nav-links {
    display: none;
  }

  .open {
    display: flex;
  }
}
 
@media screen and (max-width: 925px) {
  .hamburger {
    display: block;
  }

  .nav-links {
    display: none;
  }

  .open {
    display: flex;
  }
}
</style>
