<template>
  <ListaTareas></ListaTareas>
  <img alt="Vue logo" src="./assets/logo.png">
  <CuadroColor ancho="500" alto="100" backgroundColor="green" contenido="Esto es el contenido"></CuadroColor>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <BotonContador/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import botonContador from './components/BotonContador.vue'
import CuadroColor from './components/CuadroColor.vue';
import ListaTareas from './components/ListaTareas.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    botonContador,
    CuadroColor,
    ListaTareas
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
