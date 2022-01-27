<template>
    <header>
        <div class="container">
            <div class="header-logo">
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
    color: $gray-color;
    background-color: white;

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

        .header-logo {
            width: 90px;

            img {
                width: 100%;
            }
        }
    
        ul {
        text-transform: uppercase;
        display: flex;

        li {
            font-size: 15px;
            font-weight: 700;
            padding: 60px 0;
            margin: 0 10px;
            border-bottom: 7px transparent solid;

            &:hover {
                color: $blue-color;
                border-bottom: 7px $blue-color solid;
            }
        }
    }

}

</style>