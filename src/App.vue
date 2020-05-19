<template>
  <div id="app">  
    <UserDetails msg="Welcome Ravi"/>
    <Experience msg="My Experience" />
    <Education />
    <Skills />
    <Software />
    <Interests />
  </div>
</template>

<script>
import UserDetails from './components/UserDetails.vue'
import Experience from './components/Experience.vue'
import Education from './components/Education.vue'
import Skills from './components/Skills.vue'
import Software from './components/Software.vue'
import Interests from './components/Interests.vue'

export default {
  name: 'App',
  components: {
    UserDetails,
    Experience,
    Education,
    Skills,
    Software,
    Interests
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 16px;
}
</style>
