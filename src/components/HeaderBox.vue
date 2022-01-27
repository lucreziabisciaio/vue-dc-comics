<template>
    <header>
        <div class="container">
            <div class="header-img">
                <img src="@/img/dc-logo.png" alt="">
            </div>
            <div class="nav-links">
                <ul>
                    <li>characters</li>
                    <li>comics</li>
                    <li>movies</li>
                    <li>tv</li>
                    <li>games</li>
                    <li>collectibles</li>
                    <li>videos</li>
                    <li>fans</li>
                    <li>news</li>
                    <li>shop</li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

header {
    color: $text-gray;
    background-color: white;
    

    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    ul {
        text-transform: uppercase;
        display: flex;

        li {
            font-size: 15px;
            font-weight: 700;
            padding: 70px 0;
            margin: 0 10px;
            border-bottom: 7px transparent solid;
            cursor: pointer;

            &:hover {
                color: $text-blue;
                border-bottom: 7px $text-blue solid;
            }
        }
    }

}

</style>