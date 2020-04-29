<template>
<div class="container">
  <div id="app">
    <expenseManagmentTemplate />
  </div>
</div>
</template>

<script>

import expenseManagmentTemplate from "./components/expenseManagmentTemplate.vue";

export default {
  name: "App",
  components: {
    expenseManagmentTemplate
  }
};
</script>

