<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <EjercicioUno msg="Welcome to Your Vue.js App"/>
    <EjercicioDos msg="Welcome to Your Vue.js App"/>
    <EjercicioTres msg="Welcome to Your Vue.js App"/>
    <EjercicioCuatro msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
//import EjercicioUno from './components/EjercicioUno.vue'
//import EjercicioDos from './components/EjercicioDos.vue'
//import EjercicioTres from './components/EjercicioTres.vue'
import EjercicioCuatro from './components/EjercicioCuatro.vue'

export default {
  name: 'App',
  components: {
    //EjercicioUno,
    //EjercicioDos,
    //EjercicioTres,
    EjercicioCuatro
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
