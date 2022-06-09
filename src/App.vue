<template>
  <div id="app">
    
    <MyHeader/>
    <main>
      <MyCorpo/>
    </main>
    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/Myheader.vue'
import MyFooter from './components/Myfooter.vue'
import MyCorpo from './components/corpo.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    MyCorpo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
