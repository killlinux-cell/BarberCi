<template>
  <section class="about" id="about">
    <div class="container">
      <h2>À Propos de Nous</h2>
      <p>Nous sommes un salon de coiffure haut de gamme...</p>
    </div>
  </section>
</template>
<script>
export default{
  name: 'About',
}
</script>

<style scoped>
.about {
  background-color: #f4f4f4;
  padding: 50px 0;
  text-align: center;
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

p {
  font-size: 1.1rem;
}
</style>
