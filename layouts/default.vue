<template>
  <div class="main-div">
    <main-nav></main-nav>
    <nuxt></nuxt>
    <main-footer></main-footer>
  </div>
</template>

<script>
import MainNav from '../components/Navbar/MainNav.vue'
import MainFooter from '../components/Navbar/MainFooter.vue'
export default {
  components: {
    MainNav,
    MainFooter
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