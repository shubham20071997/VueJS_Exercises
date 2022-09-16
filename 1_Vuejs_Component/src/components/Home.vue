<template>
<div>
<h1> template in vuejs</h1>
<!-- <h1> Hello from home component</h1> -->
 <!-- <h1> For loop in vuejs</h1>
 <table border="2px">
 <tr>
 <td>Id</td>
 <td>Name </td>
 <td>Email</td>
 </tr>
 <tr v-for="user in users" :key="user.id">
 <td>{{user.id}}</td>
 <td>{{user.name}}</td>
 <td>{{user.email}}</td>
 </tr>
</table> -->
 
<!-- <h1 v-if="show"> Conditional rendering in vuejs</h1>
<h1 v-else> the if-else property</h1>
<button v-on:click="display">Toogle</button> -->
<!-- <h1>{{data}}</h1>
<h1>{{msg}}</h1>
<button v-on:click="hello">call hello function </button> 
<button v-on:mouseover="hello">call hello function </button> -->
</div>
</template>

<script>
export default{
    name:'Home',
    // props:{
    //     data:String,
    //     msg: String
    };
// data(){
//     return{
//         users:
//         [
//             {id:1, name:"peter", email:'peter@test.com'},
//             {id:2, name:"sam", email:'sam@test.com'},
//             {id:3, name:"bruny", email:'bruny@test.com'},
//             {id:4, name:"bruce", email:'bruce@test.com'}
//         ]
//     }
// }, 
// data(){
//     return{
//         //show:true
//         show:false
//     }
// },
    // methods:{
    //     display()
    //     {
    //         this.show=!this.show
    //     }
    // },
    // methods:{
    //     hello()
    //     {
    //         alert("hello function called")
    //     }
    // }
//}

</script>