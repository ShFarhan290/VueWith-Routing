<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navber.vue'
import Footer from './components/Footer.vue'
</script>

<template>

  
  <main class="flex-shrink-0">
    <Navbar></Navbar>
    <RouterView />
  </main>

  <Footer></Footer>

  
</template>

<style scoped>

</style>
