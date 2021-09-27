<template>
  <div class="main-div">
    <main-nav></main-nav>
    <nuxt></nuxt>
  </div>
</template>

<script>
import MainNav from '../components/Navbar/MainNav.vue'
export default {
  components: {
    MainNav
  }
}
</script>

<style scoped>
.main-div{
  background-color: rgb(196, 196, 196);
  height: auto;
  font-family: monospace;
}
</style>