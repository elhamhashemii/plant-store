<template>
    <div class="social">
        <div class="my-icons">
            <span class="my-icon">
                <img src="~static/facebook.png" alt="">
            </span>           
            <span class="my-icon">
                <img src="~static/instagram.png" alt="">
            </span>
            <span class="my-icon">
                <img src="~static/twitter.png" alt="">
            </span>        
            <span class="line"></span>
        </div>
    </div>
</template>

<style scoped>
.social{
    margin-top: 200px;
}
.my-icons{
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    
}
.my-icon img{
    cursor: pointer;
    margin-bottom: 20px;
    width: 20px;
    height: 20px;
}
.line {
    border-left: 2px solid #1A3237;
    height: 228px;
    margin-right: 8px;
}
</style>