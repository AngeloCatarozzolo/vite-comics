<script setup>
import { ref } from 'vue'

</script>

<!--------------------------------->

<template>
    <div class="container">
        <div class="container-black">
            <h1> &#8594 Content goes here &#8592 </h1>
        </div>
        <div class="container-blue">
            <div class="card">
                <img src="../assets/buy-comics-digital-comics.png" alt="DigitalComics">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="card">
                <img src="../assets/buy-comics-merchandise.png" alt="Merch">
                <p>DC MERCHANDISE</p>
            </div>
            <div class="card">
                <img src="../assets/buy-comics-subscriptions.png" alt="Subscriptions">
                <p>SUBSCRIPTION</p>
            </div>
            <div class="card">
                <img src="../assets/buy-comics-shop-locator.png" alt="ShopLocator">
                <p>COMIC SHOP LOCATOR</p>
            </div>
            <div class="card">
                <img src="../assets/buy-dc-power-visa.svg" alt="PowerVisa">
                <p>DC POWER VISA</p>
            </div>
        </div>
    </div>
</template>

<!--------------------------------->

<style lang="scss" scoped>
.container{
    background-color: #0282f9;
    .container-black{
        height: 8.125rem;
        background-color: #1c1c1c;
        
        h1{
            display: flex;
            float: left;
            margin-left: 9.375rem;
            margin-top: 2.5rem;
            color: white;

        }
    }
    .container-blue{
        height: 8.125rem;
        display: flex;
        justify-content: center;
        align-items: center;

        .card{
            display: flex;
            margin-right: 3.125rem;
        }

        img{
            height: 3.125rem;
        }
            
        p{
            color: white;
            margin-left: .625rem;
            font-family: 'Open Sans', sans-serif;
        }
    }
}

</style>