<script setup>
import {  RouterView } from 'vue-router'
import Nav from "./components/Nav.vue"
import Sidebar from './components/Sidebar.vue';
</script>

<template>
  
    
      <Nav />
    <Sidebar />
  <div class="ml-64 p-24 h-80 rounded-md">
  <RouterView />
  </div>
    
</template>

<style scoped>
 
</style>