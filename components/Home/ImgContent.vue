<template>
    <div class="img-box">
        <div class="main-pic">
            <img src="~static/Icons/plant.png" alt="">
        </div>
    </div>
</template>

<style scoped>
.img-box{
    border-radius: 50%;
    background: linear-gradient(to top right, #D5EEC6, #9CC485);
    height: 75vh;
    margin-top: 80px;
    position: relative;
}
.main-pic{
    position: absolute;
    top: 100px;
    right: 80px;
    z-index: 3;
}
.main-pic img{
    width: 300px;
    height: 300px;
}
</style>