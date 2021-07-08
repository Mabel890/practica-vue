<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <EjercicioTres msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import EjercicioTres from './components/EjercicioTres.vue'

export default {
  name: 'App',
  components: {
    EjercicioTres
  }
}
</script>
<!-- Ejercicio 2, suma de dos valores
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <EjercicioDos msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import EjercicioDos from './components/EjercicioDos.vue'

export default {
  name: 'App',
  components: {
    EjercicioDos
  }
}
</script>
-->

<!-- Ejercicio 1
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <EjercicioUno msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import EjercicioUno from './components/EjercicioUno.vue'

export default {
  name: 'App',
  components: {
    EjercicioUno
  }
}
</script>
-->
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
