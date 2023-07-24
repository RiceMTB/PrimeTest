<template>
  <div id="app" >
 
    <primeHeader/>
    <textbox mylabel="Who can see this?"/>
    <datepick mylabel="A Date"/>
    <textbox mylabel="Another Date"/>
    <textbox mylabel="Where did this come from?"/>
    <textbox mylabel="Title of this thing"/>
    <atextbox mylabel='Summary' :myrow = "10" :mycol= "50"/>
     <textbox mylabel="Web link to this thing"/>
    <dropdown/>
     <primeHeader/>

  </div>
</template>

<script>
import datepick from './components/widgit/datepicker.vue'
import primeTest from './components/primeTest_1.vue'
import primeHeader from './components/primeHeader.vue'
import atextbox from './components/texbox.vue'
import sidebar from './components/sidebar/main_sidebar.vue'
import dropdown from './components/widgit/dropdown.vue'
import textbox from  './components/widgit/textentry.vue'
export default {
  name: 'App',
  components: { 
    datepick,
   
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
  margin-top: 0px;
}
</style>
