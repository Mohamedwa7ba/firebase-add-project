<template>

  <Navbar />
  <router-view  />

</template>

<script lang="ts" setup>
import Navbar from './components/Navbar.vue'
</script>

<style>
#app {
font-family: Avenir, Helvetica, Arial, sans-serif;
-webkit-font-smoothing: antialiased;
-moz-osx-font-smoothing: grayscale;
color: #2c3e50;
}
</style>