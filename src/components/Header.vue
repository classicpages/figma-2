<template>
        <nav class="flex">
            <p class="site">Shopping Site</p>
                <div class="flex navbar">
                  <div class="navbars">Home</div>
                  <div class="navbar">About</div>
                  <div class="navbar">Contact</div>
                  <div class="navbar">Testimonials</div>
                  <div class="navbar">SignIn</div>
                  <div><button class="btn">SignUp</button></div>
                </div>
        </nav>
  <Button />


   


    
   
</template>


<script setup>
import Button from '@/components/Button.vue'
</script>
<style scoped>
.navbar {
    width: 100px;
    height: 58px;
    text-align: right;
    margin-left: 70px;
    display: flex;
}

.navbars {
    margin-left: 500px;
}
.site {
    color: #D82CD1;
    margin-top: 20px;
    margin-left: 20px;
    font-size: 15px;
    font-weight: 700;
    float: left;
}

.btn {
    background-color: #D82CD1;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 35px;
    padding-right: 35px;
    border-radius: 6px;
    color: #fff;
    font-size: 13px;
    margin-left: 30px;
}
</style>