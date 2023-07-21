<template>
  <div id="app">
 
    <primeHeader/>
    <textbox mylabel="Who can see this?"/>
    <atextbox mylabel='Summary' :myrow = "10" :mycol= "50"/>
    <dropdown/>
     <primeHeader/>

  </div>
</template>

<script>

import primeTest from './components/primeTest_1.vue'
import primeHeader from './components/primeHeader.vue'
import atextbox from './components/texbox.vue'
import sidebar from './components/sidebar/main_sidebar.vue'
import dropdown from './components/widgit/dropdown.vue'
import textbox from  './components/widgit/textentry.vue'
export default {
  name: 'App',
  components: {
   
    primeTest,
    primeHeader,
    atextbox,
    sidebar,
    dropdown,
    textbox
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
