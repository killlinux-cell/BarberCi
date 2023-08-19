<template>
  <section class="gallery" id="gallerie">
    <div class="container">
      <div class="image"><img src="../assets/price-2.jpg" alt="Coiffure 1"></div>
      <div class="image"><img src="../assets/price-3.jpg" alt="Coiffure 2"></div>
      <div class="image"><img src="../assets/price-4.jpg" alt="Coiffure 3"></div>
    </div>
  </section>
</template>

<script>
export default{
  name: 'Gallerie',
}
</script>

<style scoped>
.gallery {
  padding: 50px 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.image img {
  max-width: 100%;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
</style>
