<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <expenseManagmentTemplate />
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import expenseManagmentTemplate from "./components/expenseManagmentTemplate.vue";

export default {
  name: "App",
  components: {
    expenseManagmentTemplate
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
