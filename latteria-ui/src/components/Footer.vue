<template>
  <div class="footer">
    <p>® 2020 - Creato da <a href="http://gerardosiebels.com">Gerardo Siebels</a></p>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
  .footer {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    background-color: rgb(72, 189, 235);
    width: 100vw;
    font-weight: 500;
    height: 50px;
  }

  a {
    text-decoration: none;
    color: rgb(58, 58, 58);
  }


</style>