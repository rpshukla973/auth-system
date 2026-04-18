<template>
  <div id="app">
    <Navbar />
    <router-view />
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue';
export default {
  components: {
    Navbar
  }
};
</script>
<style>
body {
  background-color: #121212;
  color: #ffffff;
}
</style>