<template>
    <img alt="DHC logo" src="./assets/images/dhc-logo.png">
    <HelloDHC msg="A welcome message at Diehardcoder"/>
</template>

<script>
    import HelloDHC from './components/HelloDHC.vue'

    export default {
        name: 'App',
        components: {
            HelloDHC
        }
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
