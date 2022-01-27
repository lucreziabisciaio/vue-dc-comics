<template>
    <div class="footer-main">
        <div class="container">
            <div class="footer-container">
                <div class="footer-links">
                    <ul>
                        <li>
                            <p>DC COMICS</p>
                        </li>

                        <li>characters</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>tv</li>
                        <li>games</li>
                        <li>collectibles</li>
                        <li>videos</li>
                        <li>fans</li>
                        <li>news</li>
                    </ul>

                    <ul>
                        <li>
                            <p>Shop</p>
                        </li>

                        <li>shop DC</li>
                        <li>shop DC collectibles</li>
                    </ul>

                    <ul>
                        <li>
                            <p>DC COMICS</p>
                        </li>

                        <li>terms of use</li>
                        <li>privacy policy (new)</li>
                        <li>ad choices</li>
                        <li>advertising</li>
                        <li>jobs</li>
                        <li>subscriptions</li>
                        <li>talent workshops</li>
                        <li>CPSC certificates</li>
                        <li>ratings</li>
                        <li>shop help</li>
                        <li>contact us</li>
                    </ul>

                    <ul>
                        <li>
                            <p>SITES</p>
                        </li>
                        
                        <li>DC</li>
                        <li>MAD magazine</li>
                        <li>DC kids</li>
                        <li>DC universe</li>
                        <li>DC power visa</li>
                    </ul>
                </div>

                <div class="footer-logo">
                    <img src="@/img/dc-logo-bg.png" alt="">
                </div>
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

.footer-main {
    background-image: url('../img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    z-index: -1;

    .container {
        width: 1200px;
        margin: 0 auto;

        .footer-container {
            max-height: 400px;
            padding: 35px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;

            .footer-links {
                max-height: 400px;
                width: 100%;
                display: flex;
                flex-direction: column;
                flex-wrap: wrap;

                p {
                    color: white;
                    font-weight: 800;
                    font-size: 20px;
                }

                ul {
                    margin: 12px 0;


                    li {
                        color: $text-light-gray;
                        text-transform: capitalize;
                        font-size: 12px;
                        margin: 5px 0;
                    }
                }
            }

            .footer-logo {
                width: 100%;

                img {
                    position: absolute;
                    top: -90px;
                    right: 0;
                    overflow: hidden;
                    z-index: 0;
                }
            }
        }
    }


}

</style>