<template>
<div>
<h1 class="homestyle">Class and Style bindings</h1>
<h1 v-bind:style="{color:'blue'}">Style bindings</h1>
<h1 v-bind:class="{display:show}">Class bindings with Object</h1>
<h1 v-bind:class="[ aclass]">Class bindings with Array</h1>
</div>
</template>

<script>
export default{
    name:'Home',
    data(){
        return{
            show:true,
            aclass:'arrayClass',
           
        }
    },
    methods:{
        
        }
    }
</script>

<style scoped>
.homestyle{
color:orange;
}
.display{
    background-color:brown;
}
.arrayClass{
   background-color:cyan; 
}
</style>