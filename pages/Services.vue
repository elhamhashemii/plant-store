<template>
    <div class="main-container">
        <our-services></our-services>
    </div>
</template>

<script>
import OurServices from '~/components/Servicess/OurServices.vue'
export default {
    components: {
        OurServices
    }
}
</script>

<style scoped>
.main-container{
    width:80%;
    margin: auto;
    padding-top: 50px;
}

</style>