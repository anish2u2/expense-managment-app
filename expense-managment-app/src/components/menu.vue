<template>
    <div :class="linkClass" :linkName="linkName" @click="onMenuClick">{{menuTitle}}</div>
</template>

<script>
    export default {
        name: "menuLinks" ,
        props:{
            linkClass:{
                type: String
                },
            linkName: {
                type: String
                },
            menuTitle: {type:String}
        },
        methods:{
            onMenuClick:function(){
                console.log("Clicked");
            }
        }

    };
</script>

<style>
     .linkClass {

    }
</style>