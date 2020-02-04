<template>
      <nav class="navb">
          <router-link class="link" to="/">Home</router-link>
          <router-link class="link" to="/storia">Storia</router-link>
          <router-link class="link" to="/produtti">Produtti</router-link>
          <router-link class="link" to="/contatti">Contatti</router-link>      
      </nav>
</template>

<script>
export default {
  name: 'Navbar'  
}
</script>

<style scoped>
.navb {
  background-color: rgb(72, 189, 235);
  height: 50px;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center
}

.link {
  margin: 0 50px;
  padding: 0 10px;
  font-weight: 400;
  text-decoration: none;
  color: white;
}

.link:hover {
  border-bottom: 2px solid white;
  justify-self: center;
}



</style>