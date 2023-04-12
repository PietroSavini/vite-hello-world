<script>
    export default {
        name: 'AppTitle',
        data(){
            return{
                title: "Vite",
            }
        }
    }
</script>

<template>
    <h1 class="title">la mia prima app con {{ title }}</h1>
</template>

<style>
    h1:hover{
        background: linear-gradient(to right, #ef5350, #f48fb1, #7e57c2, #2196f3, #26c6da, #43a047, #eeff41, #f9a825, #ff5722);
        filter: drop-shadow(0 0 0.75rem rgb(190, 34, 10));
        transform: scale(1.5);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }
</style>