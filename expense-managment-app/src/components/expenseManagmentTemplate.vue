
<template>
<div>
  <div class="clearfix">
    <br/><br/>
  </div>

    <headerTemplate :heading='expenseManagmentHeading' :subHeading='expenseManagmentSubHeading'/>
    <menuBar :searchPlaceHolder="searchPlaceHolder" :searchButtonTitle="searchButtonTitle"/>
</div>
</template>

<script>
import headerTemplate from "./header";
import menuBar from "./menuBar";
export default {
  name: "expenseManagmentTemplate",
  components: {
   headerTemplate,
   menuBar
  },data:function(){
    return {
      expenseManagmentHeading:"Expense Managment System",
      expenseManagmentSubHeading:"Manage your expenses easily....",
      searchPlaceHolder:"Seach here..",
      searchButtonTitle:"Seach"
    };
  }
};
</script>

