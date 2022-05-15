<script setup>
import NavBar from './components/NavBar.vue'
import Header from './components/Header.vue'
import Firmas from './components/Firmas.vue'
import ProgressBar from './components/ProgressBar.vue'
import AboutUs from './components/AboutUs.vue';
import MapView from './components/mapView.vue';
</script>

<template> 
<div class="Header">
  <NavBar />
  <Header />
</div>
<MapView />
<AboutUs />
<ProgressBar />
<Firmas />
</template>

<style>
body{margin:0}
.Header{
  background-image: url(../src/assets/Logos/Portada.svg);
  background-position: 30%;
}
</style>
