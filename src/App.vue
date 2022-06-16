<template>
  <div id="app" >
   <HeaderDc/>
   <MainDc/>
   <BlueFooter/>
   <ComicFooter/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderDc from './components/HeaderDc.vue'
import MainDc from './components/MainDc.vue'
import BlueFooter from './components/BlueFooter.vue'
import ComicFooter from './components/ComicFooter.vue'


export default {
  name: 'App',
  components: {
   // HelloWorld,
   HeaderDc,
   MainDc,
   BlueFooter,
   ComicFooter
  }
}
</script>

<style lang="scss">
// #app {
//   padding: 2px;
// }
 
</style>
