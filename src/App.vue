<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Nim />
  </div>
</template>

<script>
import Nim from "./components/Nim";

export default {
  name: "app",
  components: {
    Nim
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
