<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/header/HeaderComponent.vue';
import FooterComponent from './components/footer/FooterComponent.vue';

</script>

<template>
  <header>
    <HeaderComponent />

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />

    <FooterComponent />

  
</template>

<style scoped>

</style>
