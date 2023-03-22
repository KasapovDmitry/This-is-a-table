<template>
 <div id="app">
    <tMain/>
 </div>
</template>

<script>
  import tMain from '@/components/t-Main';

export default {
  name: 'App',
  components: {
    tMain
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
