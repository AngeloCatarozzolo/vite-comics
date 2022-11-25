<script setup>
import { ref } from 'vue'

</script>

<!--------------------------------->

<template>
    <div class="backgroundImage">
        <div class="liste">
            <div class="doppiaLista">
                <div class="lista1">
                    <ul>
                        <p><strong>DC COMICS</strong></p>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                </div>
                <div class="lista2">
                    <ul>
                        <p><strong>SHOP</strong></p>
                        <li>Shop DC</li>
                        <li>Shop DC collectibles</li>
                    </ul>
                </div>
            </div>
            <div class="listaDc">
                <ul>
                    <p><strong>DC</strong></p>
                    <li>Terms of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choise</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPCS Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div class="listaSites">
                <ul>        
                    <p><strong>SITES</strong></p>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
        <div class="img">
            <img src="../assets/dc-logo-bg.png" alt="logoDc">
        </div>    
    </div>
</template>

<!--------------------------------->

<style lang="scss" scoped>
    .backgroundImage{
        background-image: url(../assets/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size:  cover;
        height: 31.25rem;
        align-items: center;
        display: flex;
        justify-content: space-between;
        overflow: hidden;
            .liste{
            display: flex;
            flex-direction: row;
            margin-left: 9.375rem;
        
             p{
                color: white;
            }
            li{
                color: gray;
                list-style: none;
            }
        }
        .img{
            overflow: hidden;
            margin-right: 10rem;
        
        }
    }
</style>