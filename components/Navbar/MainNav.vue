<template>
    <div class="my-nav">
        <div class="main-nav" v-if="!smallScreen">
            <h2 class="logo">
                <img src="~/static/Icons/vegan.png" alt="">
                Plant Buddy
                </h2>
            <ul class="nav-items">
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><nuxt-link to="/services">Our Serivces</nuxt-link></li>
                <li><nuxt-link to="/products">Our Products</nuxt-link></li>
                <li><nuxt-link to="/contact">Contact Us</nuxt-link></li>
            </ul>
        </div>
        <div class="side-nav" v-if="!smallScreen">
            <side-nav></side-nav>
        </div>
        <small-nav v-if="smallScreen"></small-nav>
    </div>
</template>

<script>
import SideNav from './SideNav.vue'
import SmallNav from './SmallNav.vue'
export default {
    components:{
        SideNav,
        SmallNav
    },
    data(){
        return{
            smallScreen: false
        }
    }
}
</script>

<style scoped>
.my-nav{
    width: 100%;
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
    align-items: center;
    
}
.main-nav{
    width: 80%;
    display: flex;
    flex-flow: row;
}
.logo{
    font-weight: bolder;
    padding-left: 70px;
    position: relative;
}
.logo img{
    position: absolute;
    top: -2px;
    left: 30px;
    width: 30px;
    height: 30px;
}
ul{
    display: flex;
    flex-direction: row;
    margin: auto;
    
}
li{
    list-style: none;
    margin-left: 60px;
}
li a{
    text-decoration: none;
    color: #142E38;
    font-weight: bolder;
    padding-bottom: 5px;
}
li a:hover{
    border-bottom: 1px solid #142E38;
}
</style>