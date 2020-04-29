<template>
   <li class="nav-item"> <div :class="linkClass" :linkName="linkName" @click="onMenuClick(this)">{{menuTitle}}</div></li>
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
            onMenuClick:function(linkObject){
                console.log("Clicked");
                console.log(linkObject);
            }
        }

    };
</script>
