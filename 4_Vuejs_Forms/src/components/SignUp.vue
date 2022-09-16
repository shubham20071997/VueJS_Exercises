<template>
<div>
<h1>Form with checkbox and radio button</h1>
<input type="text" placeholder="enter your name" v-model="signup.username"/><br><br>
<input type="password" placeholder="enter your password" v-model="signup.password"/><br><br>
<p> choose hobbies</p>
<input type="checkbox" id="cricket" value="cricket"/>
<label for="cricket">cricket</label>
<input type="checkbox" id="footbal" value="footbal"/>
<label for="footbal">footbal</label><br><br>
<p> select gender</p>
<input type="radio" id="male" value="male"/>
<label for="male">male</label>
<input type="radio" id="female" value="female"/>
<label for="female">female</label>
</div>
</template>

<script>
export default{
    name:'SignUp',
    data(){
        return{
            signup:{
                username:null,
                password:null,
                hobbies:[],
                gender:null
                
            }
        }
    }
    };

</script>