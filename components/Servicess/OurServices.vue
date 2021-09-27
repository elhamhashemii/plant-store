<template>
    <div class="services">
        <div class="service">
            <div class="service-text">
                    <h2>We Design Your Plants!</h2>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam laudantium illum
                        facere vel fugit ab at necessitatibus nemo tempore ducimus optio illo reiciendis similique
                        maiores deserunt, error ad. Beatae blanditiis voluptas, perspiciatis nemo totam adipisci possimus
                        error ipsam nisi veritatis nesciunt tempora fugiat tempore quibusdam minima temporibus ut, aliquam nostrum.
                    </p>
                </div>
                <div class="service-img">
                    <img src="~/static/Pics/services.jpg" alt="">
                </div>
        </div>
        <div class="service">
                <div class="service-text">
                    <h2>Service</h2>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam laudantium illum
                        facere vel fugit ab at necessitatibus nemo tempore ducimus optio illo reiciendis similique
                        maiores deserunt, error ad. Beatae blanditiis voluptas, perspiciatis nemo totam adipisci possimus
                        error ipsam nisi veritatis nesciunt tempora fugiat tempore quibusdam minima temporibus ut, aliquam nostrum.
                    </p>
                </div>
                <div class="service-img">
                    <img src="~/static/Pics/services2.png" alt="">
                </div>
        </div>
        <div class="service">
            <div class="service-text">
                    <h2>Service</h2>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam laudantium illum
                        facere vel fugit ab at necessitatibus nemo tempore ducimus optio illo reiciendis similique
                        maiores deserunt, error ad. Beatae blanditiis voluptas, perspiciatis nemo totam adipisci possimus
                        error ipsam nisi veritatis nesciunt tempora fugiat tempore quibusdam minima temporibus ut, aliquam nostrum.
                    </p>
                </div>
                <div class="service-img">
                    <img src="~/static/Pics/services1.jpg" alt="">
                </div>
        </div>
        
    </div>
</template>

<script>
export default {
    // updated: {
        
    // }
}
</script>

<style scoped>
.services{
    display: flex;
    flex-direction: column;
    width: 100%;
}
.service{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 30px 0;
    padding: 20px;
}
.service-img{
    text-align: center;
    
}
.service-img img{
    height: 450px;
    width: 350px;
    border-radius: 10px;
}
.service-text{
    margin-top: 20px;
}
h2{
    color: #122902;
    border-right: 1px dashed #122902;
    border-bottom: 1px dashed #122902;
    width: fit-content;
    padding: 5px;

}
p{
    padding: 20px;
    margin: 40px 50px 40px 20px;
    border: 1px solid black;
}
</style>