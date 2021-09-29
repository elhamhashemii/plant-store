<template>
  <div class="v-container home-page">
    <text-content class="col-lg-6 col-md-12"></text-content>
    <img-content class="col-lg-4 col-md-12"></img-content>
    <social-bar class="col-lg-2 col-md-12"></social-bar>
  </div>
</template>

<script>
import SocialBar from '../components/Home/SocialBar.vue';
import TextContent from '../components/Home/TextContent.vue';
import ImgContent from '../components/Home/ImgContent.vue';
export default {
  components:{
    TextContent,
    ImgContent,
    SocialBar,
  }
  
}
</script>

<style scoped>
.home-page{
  display: flex;
  flex-flow: row wrap;
  margin: 50px;
}
</style>