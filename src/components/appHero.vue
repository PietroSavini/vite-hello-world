<script>    
    import AppTitle from "./appTitle.vue";
    export default {
    name: 'AppHero',
    components:{
        AppTitle,
    },
    data(){
        return{
           
        }
    }
}
</script>

<template>
    <div class= "container">
        <AppTitle/>
    </div>
</template>

<style>
    .container{
        height: 100vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        
    }
</style>