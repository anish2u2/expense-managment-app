<template>
    <div id="menuBar">
        <div id="menus" class="nav nav-tabs float-left">
            <menuLinks linkClass="nav-link" linkName="fetchExpenses" menuTitle="Read All Expenses"/>
            <menuLinks linkClass="nav-link" linkName="createExpenses" menuTitle="Create Expenses"/>
            <menuLinks linkClass="nav-link" linkName="deleteExpenses" menuTitle="Delete Expenses"/>
            <menuLinks linkClass="nav-link" linkName="updateExpenses" menuTitle="Update Expenses"/>
            
        </div>
        <nav class="navbar navbar-expand-sm bg-dark navbar-dark float-right">
              <div class="form-inline">
                <input v-model="searchQuery" class="form-control mr-sm-2" type="text" :placeholder="searchPlaceHolder">
                <button class="btn btn-success" type="button" @click="search()">{{searchButtonTitle}}</button>
              </div>
        </nav>
    </div>
</template>

<script>
import menuLinks from "./menu";
export default {
    name: "menuBar",
    components:{
        menuLinks
    },
    props:{
        searchButtonTitle:{
            type:String
        },
        searchPlaceHolder:{
            type:String
        }
    },
    data:function(){
        return {
        };
    },
    methods:{
        search:function(){
            console.log("Input data:"+this.searchQuery);
        }
    }
};
</script>