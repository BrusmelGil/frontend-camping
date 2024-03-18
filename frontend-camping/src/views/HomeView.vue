<script setup>

import BannerComponent from '@/components/banner/BannerComponent.vue';


</script>

<template>

<BannerComponent />
<div class="banner">
    <router-link to="/">
    <h1>MEJORANDO TUS VACACIONES</h1>
    </router-link>
</div>



</template>

<style>

.banner{
    background-image: url(../../src/assets/image/isla-maldivas_74190-477.png); 
    display: flex; 
    justify-content: center; 
    align-items: center; 
    width: 100%;
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    color:rgb(1, 50, 27);
    font-size: xx-large;
    font-weight: 900;
    

}


</style>