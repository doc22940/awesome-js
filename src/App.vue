<template>
  <div id="app">
    <Navbar/>
    <section class="container">
      <cards></cards>
    </section>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Cards from "./components/Cards.vue";

export default {
  name: "app",
  components: {
    Navbar,
    Cards
  }
};
</script>

<style>
body {
  height: 100%;
  /* background-image: url(./assets/geometry.png); */
  background-color: #f2f9ff;
}

#app {
  font-family: "Product Sans", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

@media (min-width: 320px) and (max-width: 480px) {
  .container {
    padding: 1.2rem;
  }
}
</style>
