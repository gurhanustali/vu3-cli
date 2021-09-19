<template>
  <h3>Vue 3 CLI Project</h3>  
  <Header title="This is from props." />
      <Circle color="blue" />
  <Circle color="red"/>
</template>

<script>

import Header from './components/Header';
import Circle from './components/Circle.vue';

export default {
  name: 'App',
  components: {
    Header,
    Circle,
  }
}
</script>

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
