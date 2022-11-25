<script setup>
import { ref } from 'vue'
</script>

<!--------------------------------->

<template>
    <div class="container">
        <div class="logo">
            <img src="../assets/dc-logo.png" alt="logo">
        </div>
        <nav>
            <ul class="nav-link">
                <li><a href="#"> characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">movies</a></li>
                <li><a href="#">tv</a></li>
                <li><a href="#">games</a></li>
                <li><a href="#">collectibles</a></li>
                <li><a href="#">video</a></li>
                <li><a href="#">fans</a></li>
                <li><a href="#">news</a></li>
                <li><a href="#">shop</a></li>
            </ul>
        </nav>
    </div>
</template>

<!--------------------------------->

<style lang="scss" scoped>
.container {
    width: 100%;
    height: 120px;
    background-color: white;
    display: flex;
    justify-content: space-between;
    
    .logo{
        height: 100px;
        width: 62.5rem;
        float: right;
        display: flex;
        justify-content: center;

    }
    nav{
        justify-content: center;
        width: 100%;
        display: flex;
        align-items: center;
        .nav-link{
            display: flex;
            justify-content: space-between;
            li{
                list-style-type: none;
                margin-right: 1.875rem;
                text-transform: uppercase
            } 
            // transition sottolineatura
                a{
                    position: relative;
                    text-decoration: none;
                    color: gray;
                    letter-spacing: .0313rem;
                    padding: 0 .625rem;
                }
                a:after{
                    content: "";
                    position: absolute;
                    background-color: #0282f9;
                    height: .3125rem;
                    width: 0;
                    left: 0;
                    bottom: -3.3125rem;
                    transition: 0.3s;
                }
                a:hover{
                    color: #0282f9;
                }
                
                a:hover:after{
                    width: 95%;
                }
        }

    }
}
</style>