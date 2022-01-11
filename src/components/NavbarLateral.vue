<template>
  <section class="home container">
    <div class="barraLateral">
      <ul class="padLeft">
        <li>
          <a href="#"><img src="../assets/home.svg" alt="" />Inicio</a>
        </li>
        <li class="select">
          <div class="options">
            <a href="#"><img src="../assets/mi-curso.svg" alt="" />Mi curso </a>
            <a href="#"> <img src="../assets/flecha.svg" alt="" /></a>
          </div>
          <ul class="list_show">
            <li class="list_inside"><a href="#">Estudiantes</a></li>
            <li class="list_inside"><a href="#">Marcar asistencia</a></li>
          </ul>
        </li>
        <li>
          <a href="#"><img src="../assets/Agenda.svg" alt="" />Agenda</a>
        </li>
        <li>
          <a href="#"><img src="../assets/comunidad.svg" alt="" />Comunidad</a>
        </li>
      </ul>
    </div>
    <Main />
  </section>
</template>

<script>
import Main from "./main.vue";

export default {
  components: {
    Main,
  },
};
</script>

<style></style>
