<template>
  <div id="app">
    
    <name />
    <about/>
    <skill/>
    <education/>
  </div>
</template>

<script>

import name from './components/name.vue'
import about from './components/about.vue'
import skill from './components/skill.vue'
import education from './components/education.vue'
export default {
  name: 'App',
  components: {
    name,about,skill,education
  }
}
</script>

<style>
#app {
  
  margin:50px;
  border:1px solid rgb(0,128,115);
  background-color:white;
  padding:10px;
  

  

  
}
</style>
