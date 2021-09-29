<template>
    <div class="small-nav">
        <div class="humb-menu" v-if="!menu">
            <img src="~/static/Icons/menu.png" @click="openMenu()">
        </div>
        <ul class="nav-items" v-if="menu">
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><nuxt-link to="/services">Our Serivces</nuxt-link></li>
                <li><nuxt-link to="/products">Our Products</nuxt-link></li>
                <li><nuxt-link to="/contact">Contact Us</nuxt-link></li>
        </ul>
    </div>
</template>

<script>
export default {
    data(){
        return{
            menu: false
        }
    },
    methods:{
        openMenu(){
            this.menu = true;
        }
    }
}
</script>

<style scoped>
.humb-menu{
    background-color: #142E38;
    padding: 10px;
    border-bottom-right-radius: 30px;
    text-align: center;
}
.humb-menu img{
    width: 50px;
    height: 50px;
    filter: invert(1);
    transform: rotate(180deg);
    cursor: pointer;
}
ul{
    display: flex;
    flex-direction: column;
    background-color: #142E38;
    padding: 10px;
}
li{
    list-style: none;
    padding: 10px;
}
li a{
    text-decoration: none;
    color: #fff;
    font-weight: bolder;
}
li:hover{
    background-color: #3d839e;
    color: #142E38;
}
li a:hover{
    color: #142E38;
}
</style>