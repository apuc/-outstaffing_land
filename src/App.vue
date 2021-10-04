<template>
  <div id="app">
    <ItOutstaffing/>
  </div>
</template>

<script>
import ItOutstaffing from './view/ItOutstaffing.vue'

export default {
  name: 'App',
  components: {
    ItOutstaffing
  }
}
</script>

<style>

@font-face {
  font-family: "G TEesti Pro Display";
  font-style: normal;
  font-weight: 400;
  /* Браузер сначала попробует найти шрифт локально */
  src:  url("assets/font/font.otf") format("otf");
}

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
