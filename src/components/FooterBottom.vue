<template>
    <div class="footer-bottom">
        <div class="container">

            <div class="sign-up">

                <div class="sign-button">
                    <p>sign-up now!</p>
                </div>
                
            </div>
            
            <div class="social-area">
                <ul>
                    <li>
                        <p>FOLLOW US</p>
                    </li>

                    <li>
                        <img src="@/img/footer-facebook.png" alt="">
                    </li>

                    <li>
                        <img src="@/img/footer-twitter.png" alt="">
                    </li>

                    <li>
                        <img src="@/img/footer-youtube.png" alt="">
                    </li>

                    <li>
                        <img src="@/img/footer-pinterest.png" alt="">
                    </li>

                    <li>
                        <img src="@/img/footer-periscope.png" alt="">
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.footer-bottom {
    background-color: $gray-color;
}

.container {
    padding: 25px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
        
.sign-button {
    border: 2px $blue-color solid;

    p {
        color: white;
        text-transform: uppercase;
        font-weight: 700;
        padding: 15px;
        cursor: pointer;
    }
}

.social-area {

    ul {
        display: flex;
        align-items: center;

        li {
            margin: 0px 10px;

            p {
                color: $blue-color;
                font-weight: 700;
                font-size: 18;
                margin: 0px 5px;
            }
        }

    }
}
    

</style>