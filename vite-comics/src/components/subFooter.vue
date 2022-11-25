<script setup>
</script>

<template>
    <div class="container">
        <div class="follow">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="social">
            <div class="txtSocial">
                <p><strong>FOLLOW US</strong></p>
            </div>
            <div class="list">
                <ul>
                    <li><img src="../assets/footer-facebook.png" alt="facebook"></li>
                    <li><img src="../assets/footer-twitter.png" alt="twitter"></li>
                    <li><img src="../assets/footer-youtube.png" alt="youtube"></li>
                    <li><img src="../assets/footer-pinterest.png" alt="pinterest"></li>
                    <li><img src="../assets/footer-periscope.png" alt="periscope"></li>      
                </ul>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .container{
        background-color: #303030;
        display: flex;
        flex-direction: row;   
        justify-content: space-between;   
        align-items: center;
        
        .follow{
            margin-left: 12.5rem;
            button{
                color: white;
                background-color: #303030;
                border-color: #0282f9;
                font-size: 1.125rem;
            }
        }
        .social{
            margin-right: 18.75rem;
            display: flex;
            flex-direction: row;
            align-items: center;
            
            ul{
                display: flex;
                flex-direction: row;
                
                li{
                    list-style-type: none;
                    margin-right: .625rem;
                }
        
                }    }
    }
</style>