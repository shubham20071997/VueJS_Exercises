<!-- for more information
https://vuejs.org/guide/essentials/template-syntax.html -->

<template>
<div>
<h1 v-html="rowHtml"></h1>
<h3 v-once> {{name}}</h3>
<h3> {{name}}</h3>
<h3> {{ok?"yes":"No"}}</h3>
<h3> {{100+13}}</h3>
<button v-bind:disabled="disableBtn" v-on:click="updatetext"> Click Me </button>

</div>
</template>

<script>
export default{
    name:'Home',
    data(){
        return{
            name:'Anil',
            ok:false,
            rowHtml:"<h1> template in vuejs</h1>",
            disableBtn:false
        }
    },
    methods:{
        updatetext(){
            // this.name="Hello peter"
            this.ok=!this.ok
        }
    }
    };
</script>