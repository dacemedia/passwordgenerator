<script setup>
import Generator from './components/AppGenerator.vue'
</script>

<template>
  <main
  id="app"
  class="bg-[url('/grain-dark.png')] min-h-screen flex font-mono items-center justify-center p-10 md:overflow-hidden"
  >
  <Generator/>
</main>
</template>

<style>
@import url('./assets/styles/binary.css')
</style>
