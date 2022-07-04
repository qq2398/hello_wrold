<template>
  <div id="app">
    <h1>App根组件</h1>
    <my-count></my-count>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MyCount from './components/count.vue';
export default {
  name: 'App',
  components: {
    // HelloWorld
    MyCount
  }
}
</script>

<style>

</style>
