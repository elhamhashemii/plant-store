<template>
    <div>
        <my-product></my-product>
    </div>
</template>

<script>
import MyProduct from '../components/Products/MyProduct.vue'
import { mapState } from 'vuex' 
export default {
    components: {
        MyProduct
    },
    computed: {
        ...mapState(['products'])
    }
}
</script>

<style scoped>
div {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
    margin-top: 70px;
    margin-bottom: 70px;
}
</style>