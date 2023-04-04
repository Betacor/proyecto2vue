<template>
    <div class="container">
        <h2>Fundamentos de Front-End</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto, facere autem dolore harum blanditiis expedita officia. Tenetur ipsam molestiae doloribus!</p>
    </div> 
    <HelloWorld />
    <ComponentDos/>   
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ComponentDos from './components/ComponentDos.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ComponentDos
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
