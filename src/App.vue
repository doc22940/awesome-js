<template>
  <div id="app">
    <Stars></Stars>
    <Navbar/>
    <section class="container">
      <cards></cards>
    </section>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Cards from "./components/Cards.vue";
import Stars from "./components/Stars.vue";

export default {
  name: "app",
  components: {
    Navbar,
    Cards,
    Stars
  }
};
</script>

<style>
body {
  height: 100%;
  /* background-image: url(./assets/geometry.png); */
  /* background-color: #f2f9ff; */
  background: -webkit-radial-gradient(
    center,
    ellipse cover,
    #27364f 0%,
    #112 50%,
    #112 100%
  );
}

html {
  overflow: scroll;
  overflow-x: hidden;
}
::-webkit-scrollbar {
  width: 0px;
  /* remove scrollbar space */
  background: transparent;
  /* optional: just make scrollbar invisible */
}
/* optional: show position indicator in red */
::-webkit-scrollbar-thumb {
  background: #ff0000;
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
