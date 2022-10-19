<template>
  <Navbar />
  <router-view />
</template>

<script>
import Navbar from "../src/components/Navbar.vue";
export default {
  components: { Navbar },
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 0 auto;
  max-width: 600px;
  color: #555;
}
body {
  background: #f2f2f2;
}
</style>
