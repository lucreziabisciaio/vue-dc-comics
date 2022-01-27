<template>
    <div class="footer-top">
        <div class="container">
            <ul>
                <li>
                    <div class="footer-top-img">
                        <img src="@/img/buy-comics-digital-comics.png" alt="">
                    </div>
                    <p>
                        digital comics
                    </p>
                    
                </li>

                <li>
                    <div class="footer-top-img">
                        <img src="@/img/buy-comics-merchandise.png" alt="">
                    </div>
                    <p>
                        dc merchandise
                    </p>
                </li>

                <li>
                    <div class="footer-top-img">
                        <img src="@/img/buy-comics-subscriptions.png" alt="">
                    </div>
                    <p>
                        subscription
                    </p>
                </li>

                <li>
                    <div class="footer-top-img">
                        <img src="@/img/buy-comics-shop-locator.png" alt="">
                    </div>
                    <p>
                        comics shop locator
                    </p>
                </li>

                <li>
                    <div class="footer-top-img">
                        <img src="@/img/buy-comics-digital-comics.png" alt="">
                    </div>
                    <p>
                        dc power visa
                    </p>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.footer-top {
    background-color: $text-blue;

    ul {
        text-transform: uppercase;
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 50px 0;

        li {
            color: white;
            font-size: 15px;
            display: flex;
            align-items: center;

            .footer-top-img {
                margin: 0 15px;
                width: 50px;

                img {
                    width: 100%;
                }
            }
        }
    }
}

</style>