<template>
<div class="container">
  <div id="app">
    <expenseManagmentTemplate />
  </div>
</div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";
import expenseManagmentTemplate from "./components/expenseManagmentTemplate.vue";

export default {
  name: "App",
  components: {
    expenseManagmentTemplate
  }
};
</script>

