<template>
  <div id="app">
    <Hero heading="working"/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue';

export default {
  name: 'app',
  components: {
    Hero,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
