<template>
  <div id="app">
    <NavBar />
    <img width="25%" src="./assets/logo.png" />

    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import NavBar from "./components/NavBar";

export default {
  name: "App",
  components: {
    HelloWorld,
    NavBar,
  },
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
