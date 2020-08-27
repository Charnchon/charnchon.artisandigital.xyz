<template>
  <div id="app">
    <HelloWorld/>
    <Home/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Home
  }
}
</script>

<style>

</style>
