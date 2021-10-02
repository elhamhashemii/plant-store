<template>
    <div>
         <div class="base-card" v-for="product in products" :key="product.id">
             <div class="p-img">
                 <img :src="product.src" alt="">
             </div>
             <div class="p-title">
                <h2>{{ product.title }}</h2>
            </div>
            <div class="p-des">
                <p>{{ product.des }}</p>
            </div>
            <div class="p-price">
                <span class="price">
                {{ product.price }}
                </span>
            </div>
            <div class="p-btn">
                <span class="buy">add to cart</span>
            </div>
         </div>
         <!-- <div class="p-img">
             <img src="~/static/Pics/1.png" alt="">
         </div> -->
    </div>
</template>

<script>
export default {
    // computed:{
    //     products(){
    //         return this.$store.getters.products;
    //     }
    // }
    data(){
        return{
            products: [
                {id: 'p1', src: "/_nuxt/static/Pics/1.png", title: 'Flower One', des: 'lorem impsum kjdoiojffncj', price: '$102'},
                {id: 'p2', src: '~/static/Pics/2.png', title: 'Flower two', des: 'lorem impsum fkvv', price: '$43'},
                {id: 'p3', src: '~/static/Pics/3.jpg', title: 'Flower three', des: 'lorem impsum xfweddfef', price: '$90'},
                {id: 'p3', src: '~/static/Pics/3.jpg', title: 'Flower three', des: 'lorem impsum xfweddfef', price: '$90'},
                {id: 'p3', src: '~/static/Pics/3.jpg', title: 'Flower three', des: 'lorem impsum xfweddfef', price: '$90'},
                {id: 'p3', src: '~/static/Pics/3.jpg', title: 'Flower three', des: 'lorem impsum xfweddfef', price: '$90'},
                {id: 'p3', src: '~/static/Pics/3.jpg', title: 'Flower three', des: 'lorem impsum xfweddfef', price: '$90'},
            ]
        };
    },
}
</script>

<style scoped>
.base-card{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: rgb(177, 177, 177);
    border-radius: 12px;
    margin: 30px 10px;
    padding: 5px;
}
.p-img,
.p-title,
.p-des,
.p-price,
.p-btn {
    margin-top: 15px;
}
.p-img img{
    width: 250px;
    height: 300px;
}

.p-des{
    padding: 0 20px;
}
.p-btn{
    margin-top: 20px;
    margin-bottom: 20px;
}
.price, .buy {
    padding: 5px 10px;
    border-radius: 10px;
    font-weight: bolder;
}
.price img,
.buy img{
    width: 20px;
    height: 20px;
}
.price:hover{
    background-color: rgb(239, 243, 11);
    color: rgb(0, 0, 0);
}
.buy:hover{
    color: gray;
}
.price{
    background-color: rgb(230, 233, 74);
    color: gray;
}
.buy{
    background-color: #0e1829;
    color: #fff;
    cursor: pointer;
    
}

</style>