<template>
  <div class="home">
    
    <header class="head">
      <h1>La Latteria</h1>
      <h3>Senza Lattosio</h3>
    </header>
    <Navbar />
  </div>
</template>

<script>
import Navbar from '../components/Navbar'

export default {
  name: "home",
  components: {
    Navbar
    
  }
};
</script>

<style scoped>
  .head {
    background-color:  rgb(72, 189, 235);
    color: white;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

</style>
