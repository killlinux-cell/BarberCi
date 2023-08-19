<template>
  <section class="contact-visit" id="visit">
    <div class="container">
      <h2>Contactez-nous et Planifiez une Visite</h2>
      <form>
        <input type="text" placeholder="Nom complet">
        <input type="email" placeholder="Adresse e-mail">
        <textarea placeholder="Votre message"></textarea>
        <button type="submit">Envoyer</button>
      </form>
      <div class="visit-info">
        <p>Adresse : 123 Rue de la Coiffure, Ville</p>
        <p>Téléphone : +01 234 567 890</p>
        <p>Horaires : Lun-Sam, 9h-18h</p>
      </div>
    </div>
  </section>
</template>

<script>
export default{
  name: 'Visite',
}
</script>

<style scoped>
.contact-visit {
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

form {
  display: grid;
  gap: 10px;
  margin-bottom: 30px;
}

input, textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

textarea {
  resize: vertical;
}

button {
  background-color: #f2a154;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #e1863e;
}

.visit-info {
  margin-top: 30px;
  font-size: 1.1rem;
}
</style>
