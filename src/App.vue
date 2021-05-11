<template>
  <div id="app">
    <Title/>
    <Formulario/>
  </div>
</template>

<script>

import Title from './components/Title.vue'
import Formulario from './components/Formulario.vue'

export default {
  name: 'App',
  components: {
    Title,
    Formulario
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  align-content: flex-start; }*/

</style>
