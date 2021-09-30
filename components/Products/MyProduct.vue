<template>
    <div class="base-card">
        <div class="p-img">
            <img src= 'src' alt="">
        </div>
        <div class="p-title">
            <h2>{{ title }}</h2>
        </div>
        <div class="p-des">
            <p>{{ des }}</p>
        </div>
        <div class="p-price">
            <span class="price">
                {{ price }}
            </span>
        </div>
        <div class="p-btn">
            <span class="buy">add to cart</span>
        </div>
    </div>
</template>

<script>
// import { mapState } from 'vuex' 
export default {
    // props: ['src', 'title', 'des', 'price'],
    data(){
        return{
            src: '../static/Pics/2.png',
            title: 'Try',
            des: 'LORedtrfgiujpoknhv',
            price: '225'
        }
    },
    // computed: {
    //     ...mapState(['products'])
    // }
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