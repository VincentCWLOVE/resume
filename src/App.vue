<template>
  <div id="app">
    <img class="headImg" src="./assets/home-bg.jpg">
    <h2>{{msg}}</h2>

    <info></info>
    <skill></skill>
    <project></project> 
    <about-me></about-me>
  </div>
</template>

<script>

import Info from './components/myinfo.vue'
import Skill from './components/skill.vue'
import Project from './components/project.vue'
import AboutMe from './components/aboutMe.vue'

export default {
  name: 'app',
  data () {
    return {
      msg: '个人简历'
    }
  },
  components:{
    Info,
    Skill,
    Project,
    AboutMe
  },

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}


a {
  color: #42b983;
}
  
img.headImg {
  border-radius: 50%;
  width: 150px;
  height: 150px;
}

</style>
