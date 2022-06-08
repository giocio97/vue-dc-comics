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
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
