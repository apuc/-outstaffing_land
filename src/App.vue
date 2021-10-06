<template>
  <div id="app">
    <ItOutstaffing/>
  </div>
</template>

<script>
import ItOutstaffing from './view/ItOutstaffing.vue'
import Vue from 'vue';
import ElementUI from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';

Vue.use(ElementUI);
export default {
  name: 'App',
  components: {
    ItOutstaffing
  }
}
</script>

<style>

body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: "G TEesti Pro Display", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
