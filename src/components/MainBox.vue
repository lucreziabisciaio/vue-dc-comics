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
@import '@/style/mainBox.scss';
</style>