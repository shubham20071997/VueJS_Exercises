<template>
<div>
<h1 style="white-space:pre-line"> {{message}}</h1>
<!-- <input type="text" v-model="message"> -->
<textarea type="text" v-model="message"/>
</div>
</template>

<script>
export default{
    name:'DataBind',
    data(){
        return{
            message:'Hi',
           
        }
    },
    methods:{
        
        }
    }
</script>