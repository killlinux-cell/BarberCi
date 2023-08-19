<template>
  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 Salon de Coiffure. Tous droits réservés.</p>
      <ul class="social-links">
        <li><a href="#"><i class="fab fa-facebook"></i></a></li>
        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
        <li><a href="#"><i class="fab fa-instagram"></i></a></li>
      </ul>
    </div>
  </footer>
</template>

<script>
export default{
  name: 'Footer',
}
</script>

<style scoped>
.footer {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

p {
  font-size: 1rem;
}

.social-links {
  list-style: none;
  display: flex;
  gap: 10px;
  margin-top: 10px;
}

.social-links a {
  color: #fff;
  font-size: 1.2rem;
  text-decoration: none;
}

/* Ajoutez les classes d'icônes de Font Awesome pour les différents réseaux sociaux */
</style>
