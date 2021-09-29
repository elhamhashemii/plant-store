<template>
    <div class="social">
        <div class="my-icons">
            <span class="my-icon">
                <img src="~static/Icons/facebook.png" alt="">
            </span>           
            <span class="my-icon">
                <img src="~static/Icons/instagram.png" alt="">
            </span>
            <span class="my-icon">
                <img src="~static/Icons/twitter.png" alt="">
            </span>        
            <span class="line" ></span>
        </div>
    </div>
</template>

<style scoped>
.social{
    position: relative;
}
.my-icons{
    display: flex;
    flex-direction: column;
    align-items: center;
    
}
.my-icon img{
    cursor: pointer;
    margin-bottom: 20px;
    width: 20px;
    height: 20px;
}
.line {
    border-left: 2px solid #1A3237;
    height: 50vh;
    position: absolute;
    bottom: -50px;
}
</style>