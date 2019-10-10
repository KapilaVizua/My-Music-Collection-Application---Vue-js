<!-- HTML part -->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />

    <HelloWorld msg="Welcome to your music  app" />
  </div>
</template>


<!-- Java Script part-->
<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>


<!-- CSS part here-->
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


