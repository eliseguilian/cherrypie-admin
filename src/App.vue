<template>
    <div id="app" >
        <nav-menu/>
        <router-view/>
    </div>
</template>

<script>
import NavMenu from './components/view-componets/nav-menu.vue';
export default {
    name: 'App',
    components: {
        'nav-menu': NavMenu
    }
};
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    padding-left: 140px;
    position: relative;
}
body,html{
    margin: 0;
    padding: 0;
}
</style>
