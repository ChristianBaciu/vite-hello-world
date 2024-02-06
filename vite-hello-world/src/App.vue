<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default{
    components: {
        AppTitle,
        AppHero,
    },
}
</script>


<template>
    <div class="contenitore">
        <AppTitle/>
        <hr>
        <AppHero/>
    </div>
</template>


<style>
.contenitore{
    background-color: darkgrey;
    width: 400px;
    padding: 10px;
    border-radius: 10px;
    margin: 0 auto;
    text-align: center;
    margin-top: 50px;
}
</style> 
