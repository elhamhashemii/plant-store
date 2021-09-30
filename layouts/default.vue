<template>
  <div class="main-div">
    <div class="navbar">
      <small-nav v-if="smScreen"></small-nav>
      <main-nav v-if="!smScreen"></main-nav>
    </div>
    <nuxt></nuxt>
    <main-footer></main-footer>
    <!-- <v-footer></v-footer> -->
  </div>
</template>

<script>
import MainNav from '../components/Navbar/MainNav.vue'
import SmallNav from '../components/Navbar/SmallNav.vue'
import MainFooter from '../components/Navbar/MainFooter.vue'
export default {
  components: {
    MainNav,
    SmallNav,
    MainFooter
  },
  data(){
    return{
      smScreen: false 
    }
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