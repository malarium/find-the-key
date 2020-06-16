<template>
  <div id="app">
    <div class="d-flex align-items-center justify-content-center">
      <img alt="Vue logo" src="./assets/key.png" />
      <h1>Find-the-key</h1>
    </div>
    <Search />
  </div>
</template>

<script>
import Search from "./components/Search.vue";

export default {
  name: "App",
  components: {
    Search
  }
};
</script>

<style lang="scss">
#app {
  h1 {
    font-family: "Lobster", cursive;
  }
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
