<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HEADER/>
    <MAIN/>
    <FOOTER/>
  </div>
</template>

<script>
import HEADER from './components/HEADER.vue';
import  MAIN from './components/MAIN.vue';
import FOOTER from './components/FOOTER.vue';

export default {
  name: 'App',
  components: {
    HEADER,
    MAIN,
    FOOTER,

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
