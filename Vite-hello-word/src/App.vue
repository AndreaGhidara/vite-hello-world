<script setup>
import HelloWorld from './components/HelloWorld.vue';
import Pulsante from './components/Pulsante.vue';
import Header from './components/Header.vue';
import Card from './components/Card.vue';
</script>

<template>
  <h2>Project in vite</h2>
  <Header/>
  <div class="d-flex justify-content-center">
    <HelloWorld />
  </div>
  <Pulsante/>
  <Card/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
