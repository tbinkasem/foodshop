<template>

    <img class="logo" alt="FoodShop Logo" src="../assets/FoodShop.png">
    <div class="signup">
        <input type="text" placeholder="ชื่อ-สกุล" v-model="name">
        <input type="email" placeholder="อีเมล์" v-model="email">
        <input type="password" placeholder="รหัสผ่าน" v-model="password">
        <button>ลงทะเบียนใช้งาน</button>
    </div>

</template>

<script>
    export default{
        name: 'SignUp',
        data(){
            return{
                name: '',
                email: '',
                password: ''
            }
        },
        methods:{

        }
    }
</script>

<style>

    .logo{
    width: 100px;
    }

    .signup input{
    display: block;
    width: 300px;
    height: 40px;
    padding-left: 20px;
    margin-bottom: 20px;
    margin-left: auto;
    margin-right: auto;
    border: 1px dashed green;

    }

    .signup button{
    color: white;
    width: 320px;
    height: 40px;
    border: 1px dashed green;
    background-color: green;
    cursor: pointer;
    }

</style>