<template>
  <div id="app">
    <sidebar/>
    <primeHeader/>
    <primeTest/>
    <atextbox mylabel='TEST' :myrow = "20" :mycol= "40"/>
    <dropdown/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import primeTest from './components/primeTest_1.vue'
import primeHeader from './components/primeHeader.vue'
import atextbox from './components/texbox.vue'
import sidebar from './components/sidebar/main_sidebar.vue'
import dropdown from './components/widgit/dropdown.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    primeTest,
    primeHeader,
    atextbox,
    sidebar,
    dropdown
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
