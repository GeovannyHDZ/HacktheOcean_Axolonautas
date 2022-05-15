<script setup>
import NavBar from './components/NavBar.vue'
import Header from './components/Header.vue'
import Firmas from './components/Firmas.vue'
import ProgressBar from './components/ProgressBar.vue'
</script>

<template>  
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<div class="Header">
  <NavBar />
  <Header />
</div>
 <ProgressBar />
  <Firmas />
  
</template>

<style>
.Header{
  background-image: url(../src/assets/Logos/Portada.svg);
  background-position: 30%;
}
</style>
