<template>
  <div id="app">
    <img src="./assets/logo.png" />
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>


<style>
@import "../css/normalize.css";
@import "../css/main.css";
</style>