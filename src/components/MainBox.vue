<template>
    <main>
       <div class="container">
           <h1>-- Content goes here --</h1>
       </div>
    </main> 
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

main {
    background-color: $text-gray;

    .container {
        width: 1200px;
        margin: 0 auto;

        h1 {
            color: white;
            font-size: 30px;
            padding: 100px 0;
        }
    }
}

</style>