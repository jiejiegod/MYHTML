<template>
     <div>
         <home-header></home-header>
         <home-swiper></home-swiper>
         <home-icons></home-icons>
     </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeIcons from './components/Icons'
//添加 HomeIcons组件
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwiper,
    HomeIcons
  }
}
</script>

<style scoped>

</style>
