<script setup>
import Desktop from './components/Desktop.vue'
import Second from './components/Second.vue'
import Vue from './components/Vue.vue';
import Puffercat from './components/Puffercat.vue'
</script>

<template>
  <main>
    <div class="h-full w-full flex content-center justify-center">
      <div class="container flex flex-col">
        <div class="top-row flex flex-row w-full h-1/2">
  <Desktop/>
  <Second/>
  </div>
  <div class="bottom-row flex flex-row w-full h-1/2">
    <Puffercat/>
    <Vue/>
  </div>
  </div>
  </div>
  </main>
</template>

<style scoped>
.container {
  height: 600px;
  width: 900px;
 }
</style>
