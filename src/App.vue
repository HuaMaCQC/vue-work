<!-- 網頁的HTML 碼 -->
<template>
  <div id="app">
    <Title />
    <Minu />
    <Content />
  </div>
</template>

<!-- 程式碼 碼 -->
<script>
import Content from './components/Content.vue';
import Minu from './components/Minu.vue';
import Title from './components/Title.vue';

export default {
  name: 'App',
  components: {
    Title,
    Minu,
    Content,
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
  /* margin-top: 60px; */
}
</style>
