<template>
<h1>Signup</h1>
<div class="register">
<input type='text' placeholder="Enter Name">
<input type='text' placeholder="Enter Email">
<input type='text' placeholder="Enter Password">
<button>Submit</button>
</div>
</template>

<style>
.form-div { height: 500px;
width: 100px;
justify-items: center; }
.register input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left:auto;
    border: 1px solid skyblue;
}
.register button{
    width: 320px;
    height: 40px;
    border:1px solid skyblue;
    background: skyblue;
    color: #fff;
    cursor: pointer;
}
</style>

<script>
// import Header from './components/Header.vue'

export default {
    name : 'signuP',
 
}
</script>