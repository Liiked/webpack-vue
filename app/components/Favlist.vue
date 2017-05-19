<template>
<div>
    <div v-for="n in 10">{{msg}}</div>
</div>
</template>

<script>
    export default {
        data () {
            return {
                msg: 'Hello World!'
            }
        }
    }
    import '../style.css'
</script>

<style>
    /*html{
        background: red;
    }*/
</style>