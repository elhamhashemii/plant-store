<template>
    <div class="side-nav">
        <div class="my-icons">
            <span class="my-icon">
                <img src="~/static/loupe.png" alt="">
            </span>
            <span class="my-icon">
                <img src="~static/user.png" alt="">
            </span>
            <span class="my-icon">
                <img src="~static/menu.png" alt="">
            </span>
        </div>
    </div>
</template>

<style scoped>
.side-nav{
    width: 250px;
    background-color: #142E38;
    padding: 20px;
    border-top-right-radius: 30px;
    border-bottom-left-radius: 20px;
}
.my-icons{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.my-icon{
    cursor: pointer;
    margin: 0 15px;
    color: #fff;
}
.my-icon img{
    filter: invert(1);
    width: 20px;
    height: 20px;
}
</style>