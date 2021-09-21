<template>
  <div class="home-page">
    <text-content style="width: 50%"></text-content>
    <img-content style="width: 35%"></img-content>
    <social-bar style="width: 10%"></social-bar>
  </div>
</template>

<script>
import TextContent from '~/components/Home/TextContent.vue';
import ImgContent from '~/components/Home/ImgContent.vue';
import SocialBar from '~/components/Home/SocialBar.vue';
export default {
  components:{
    TextContent,
    ImgContent,
    SocialBar
  }
  
}
</script>

<style scoped>
.home-page{
  display: flex;
  width: 100%;
  height: 100vh;
}
</style>