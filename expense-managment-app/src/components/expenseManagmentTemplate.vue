
<template>
<div>
    <div class="jumbotron text-center">
          <h1>Expense Managment System</h1>
          <p>Manage your expenses easily..</p>
    </div>
    
    <div id="menus" class="nav nav-tabs">
        <menuLinks linkClass="nav-link" linkName="fetchExpenses" menuTitle="Read All Expenses"/>
        <menuLinks linkClass="nav-link" linkName="createExpenses" menuTitle="Create Expenses"/>
        <menuLinks linkClass="nav-link" linkName="deleteExpenses" menuTitle="Delete Expenses"/>
        <menuLinks linkClass="nav-link" linkName="updateExpenses" menuTitle="Update Expenses"/>
        <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
          <form class="form-inline" action="/action_page.php">
            <input class="form-control mr-sm-2" type="text" placeholder="Search">
            <button class="btn btn-success" type="submit">Search</button>
          </form>
        </nav>
    </div>
</div>
</template>

<script>

import menuLinks from "./menu";
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";
export default {
  name: "expenseManagmentTemplate",
  components: {
    menuLinks
  }
};
</script>

