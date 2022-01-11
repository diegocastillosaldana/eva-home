<template>
  <div>
    <Navbar />
    <NavbarLateral />
  </div>
</template>

<script>
import "./css/App.css";
import Navbar from "./components/Navbar.vue";
import NavbarLateral from "./components/NavbarLateral.vue";

export default {
  components: {
    Navbar,
    NavbarLateral,
  },
};
</script>

<style></style>
