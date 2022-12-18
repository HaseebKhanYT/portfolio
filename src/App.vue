<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Home from '@/views/Home.vue';
import Component from 'vue-class-component';


export default class App extends Vue {
  
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #8c9eb0;
}

.full-height{
  height: 100vh;
}

</style>
