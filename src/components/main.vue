<template>
  <div class="main">
    <h1 class="title">Estudiantes</h1>
    <form class="search-container">
      <input type="text" id="search-bar" placeholder="Buscar" />
      <a href="#"
        ><img class="search-icon" src="../assets/lupa.svg" alt=""
      /></a>
    </form>
    <div class="info">
      <h2 class="subTitle">Número de participantes: 28</h2>
      <a href="#" class="descarga">Descargar lista</a>
    </div>
    <Card />
  </div>
</template>

<script>
import Card from "../components/Card.vue";

export default {
  components: {
    Card,
  },
};
</script>

<style></style>
