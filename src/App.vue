<template>
  <div id="app">
    <counte />
  </div>
</template>

<script>
import counte from "./counte.vue";

export default {
  name: "App",
  components: {
    counte
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
