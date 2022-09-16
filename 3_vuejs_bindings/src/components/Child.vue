<template>
<div>
<h1>child component</h1>
<h3>{{name}}</h3>
</div>
</template>

<script>
export default{
    name:'Child',
    props:['name']
};
           
   
</script>