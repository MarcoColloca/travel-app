<script>
    import AppHome from '../pages/AppHome.vue';


    export default {
        data(){
            return{

            }
        },

        components:{
            AppHome
        }
    }
</script>



<template>
    <!-- Page Main -->
    <main>
        <div class="container">
            <h1 class="text-center text-danger">
                Titolo del Sito
            </h1>
        </div>

        <AppHome></AppHome>
    </main>
</template>



<style lang="scss" scoped>
    main{
        padding: 30px 0;
    }
</style>