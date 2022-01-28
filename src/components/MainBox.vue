<template>
    <main>
       <div class="container">
            <div class="card-box">
                <div class="card" v-for="(card, index) in cardList" :key="index">
                    <div class="card-img">
                        <img :src="card.thumb" alt="">
                    </div>
                    
                    <div class="card-title">
                        <p>{{ card.series }}</p>
                    </div>
                </div>
            </div>

            <div class="load-more">
                <div class="load-button">
                    <p>load more</p>
                </div>   
            </div>
           
       </div>
    </main> 
</template>

<script>
export default {
    props: {
        cardList: Array,
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

main {
    background-color: #1C1C1C;

    .card-box {
        width: 100%;
        padding: 30px 0;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        
        .card {
            width: calc((100% / 6) - 20px);
            padding: 0 10px;
            margin: 15px 0;

            .card-img {
                width: 100%;
                height: 150px;
                overflow: hidden;

                img {
                    width: 100%;
                }  
            }

            p {
                color: white;
                text-transform: uppercase;
                font-weight: 700;
                font-size: 15px;
                padding: 5px 0;
            }
            
        }
    }

    .load-more {
        display: flex;
        justify-content: center;
        align-items: center;

        .load-button {
            margin: 15px 0 25px 0;
            
            p {
                color: white;
                font-size: 15px;
                font-weight: 700;
                text-transform: uppercase;
                padding: 10px 55px;
                background-color: $blue-color;
                cursor: pointer;
            }    
        }
    }
}

</style>