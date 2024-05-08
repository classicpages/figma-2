<template>
    <section>
    <div class="welcome">
    <h1> Welcome To <span>Shopping Site</span></h1>
   </div>
   <div class="heel">
    <p class="text">Slingback fabric heels. Thin wraparound ankle starp. <br>
     Squared heel and toe. Pointed toes.
      Padded insole with <br> geometrical design. </p>
    </div>
    
    <div class="us">
        <button class="btn">Contact Us</button>
        <a class="watch" href="#">watch video</a>
    </div>
    <Button />
</section>
</template>

<script setup>
import Button from '@/components/Button.vue'
</script>


<style scoped>
nav {
    text-align: right;
    word-spacing: 40px;
    margin-top: 0;
    padding-top: 0;
}

.watch {
    margin-left: 20px;

}

.page {
    background-color: #F2F2F2;
}

.us {
    margin-top: 30px;
    margin-left: 600px;
}

.btn {
    background-color: #D82CD1;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 35px;
    padding-right: 35px;
    border-radius: 6px;
    color: #fff;
    font-size: 14px;
}

.welcome {
    text-align: center;
    margin-top: 200px;
    margin-left: 250px;
    width: 820px;
    height: 160px;
    top: 276px;
    left: 297px;
    font-weight: 800;
    font-size: 66px;
    line-height: 80px;
    letter-spacing: -5%;
}

.heel {
    text-align: center;
    margin-top: 20px;
}

.text {
    font-size: 15px;

}
</style>