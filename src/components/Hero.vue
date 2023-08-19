<template>
  <section class="hero" id="hero">
    <div class="overlay"></div>
    <div class="container">
      <h1>Bienvenue dans notre Salon de Coiffure</h1>
      <p>Offrant des services de coiffure exceptionnels depuis 10 ans.</p>
      <a href="#" class="cta-button">Prendre un rendez-vous</a>
    </div>
  </section>
</template>

<script>

export default{
  name: 'Hero',
}
</script>

<style scoped>
.hero {
  position: relative;
  background-image: url('../assets/team-2.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  color: #fff;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}

.container {
  z-index: 1;
  max-width: 800px;
  margin: 0 auto;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

p {
  font-size: 1.2rem;
  margin-bottom: 30px;
}

.cta-button {
  display: inline-block;
  background-color: #f2a154;
  color: #fff;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #e1863e;
}
</style>
