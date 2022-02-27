<!-- 網頁的HTML 碼 -->
<template>
  <div id="app">
    <HeadA />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<!-- 程式碼 碼 -->
<script>
import HelloWorld from './components/HelloWorld.vue'
import HeadA from './components/HeadA.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    HeadA,
  }
}
</script>

<!-- css -->
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
