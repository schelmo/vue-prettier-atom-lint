<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" some-long-attribute-name="a-long-attribute-value" />
    <HelloWorld msg="Welcome to Your Vue.js App" another-long-attribute-name="another-long-attribute-value" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
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
