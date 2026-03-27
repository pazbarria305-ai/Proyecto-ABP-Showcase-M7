<template>
  
  <NavbarComp />

  <RouterView />
</template>


<script setup>
import { RouterView } from 'vue-router';
import NavbarComp from './components/NavBarComp.vue';

</script>

<style scoped>

</style>