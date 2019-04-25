<template>
    <div class="home">
         <home-header></home-header>
         <home-nav></home-nav>
         <home-content></home-content>
         <home-tech></home-tech>
         <home-project ></home-project >
    </div>
   
</template>

<script>
import HomeHeader from './components/Header'
import HomeNav from './components/Nav'
import HomeContent from './components/content'
import HomeTech from './components/Tech'
import HomeProject from './components/project'
export default {
    name:'Home',
    components:{
        HomeHeader,
        HomeNav,
        HomeContent,
        HomeTech,
        HomeProject
    }
}
</script>

<style scoped>
.home{
    
    width: 100%;
    height: 1000px;
}
</style>
