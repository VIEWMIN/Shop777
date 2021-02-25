<template>
  <div id="app">
    <Header />
    <div class="main">
      <div class="container">
        <div class="row">
          <div class="col-2"></div>
          <div class="col-10"><Shop /></div>
        </div>
        <div class="row">
          <div class="col-4"></div>
          <div class="col-4"><Cart /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header";
import Shop from "./components/Shop";
import Cart from "./components/Cart";

export default {
  name: "App",
  components: {
    Shop,
    Header,
    Cart,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0026ff;
  background-image: var(---bs-gradient);
  background-color: #c061ff9a;
}
</style>