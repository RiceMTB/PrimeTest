<template>
  <div id="app">
    <primeHeader/>
    <primeTest/>
    <atextbox mylabel='TEST' :myrow = "20" :mycol= "40"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import primeTest from './components/primeTest_1.vue'
import primeHeader from './components/primeHeader.vue'
import atextbox from './components/texbox.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    primeTest,
    primeHeader,
    atextbox
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
