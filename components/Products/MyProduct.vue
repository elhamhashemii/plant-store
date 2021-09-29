<template>
    <div class="base-card">
        <div class="p-img">
            <img src="~/static/Pics/1.png" alt="">
        </div>
        <div class="p-title">
            <h2>Title</h2>
        </div>
        <div class="p-des">
            <p>Lorem ipsum dolor sit amet.</p>
        </div>
        <div class="p-price">
            <span class="price">
                <!-- <img src="~/static/Icons/save-money.png" alt=""> -->
                $100
            </span>
        </div>
        <div class="p-btn">
            <span class="buy">
                add to cart
                <!-- <img src="~/static/Icons/shopping-cart.png" alt=""> -->
            </span>
        </div>
    </div>
</template>

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