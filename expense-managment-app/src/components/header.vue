<template>
    <div class="jumbotron text-center">
          <h1>{{heading}}</h1>
          <p>{{subHeading}}</p>
    </div>
</template>

<script>
export default {
    name:   "header-template",
    props:{
        heading:{
            type:String
        },
        subHeading:{
            type:String
        }
    }    
};
</script>