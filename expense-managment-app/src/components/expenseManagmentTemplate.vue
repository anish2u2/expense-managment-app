
<template>
    <div id="menus">
        <menuLinks linkClass="menuLink" linkName="fetchExpenses" menuTitle="Read All Expenses"/>
        <menuLinks linkClass="menuLink" linkName="createExpenses" menuTitle="Create Expenses"/>
        <menuLinks linkClass="menuLink" linkName="deleteExpenses" menuTitle="Delete Expenses"/>
        <menuLinks linkClass="menuLink" linkName="updateExpenses" menuTitle="Update Expenses"/>
    </div>
</template>

<script>

import menuLinks from "./menu";

export default {
  name: "expenseManagmentTemplate",
  components: {
    menuLinks
  }
};
</script>