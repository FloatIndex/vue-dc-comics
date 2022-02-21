<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MyFooterTop/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooterTop from './components/MyFooterTop.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooterTop
  }
}
</script>

<style lang="scss">
@import "./assets/style/general.scss"
</style>
