<template>
    <img class="logo" src="../assets/download.png" alt="">
    <h1>Sign Up</h1>

    <div class="register">
        <input type="text" placeholder="Enter Name">
        <input type="text" placeholder="Enter Email">
        <input type="password" placeholder="Enter Password">
        <button>Sign Up</button>
    </div>
</template>

<script>
export default {
    name: 'SignUp',
    data(){
        return {
            name:'',
            email:'',
            password:''

        }
    }
}
</script>

<style>
.logo {
    width: 100px;
}

.register input {
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;
}

.register button {
    width: 320px;
    height: 40px;
    border: 1px solid rgb(64, 60, 101);
    background: skyblue;
    color: white;
    cursor: pointer;
}
</style>