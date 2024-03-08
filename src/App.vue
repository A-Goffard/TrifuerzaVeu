<template>
  <div>
    <Equipo msg="Trifuerza"/>
  </div>
</template>

<script>
import Equipo from './components/Equipo.vue'/* esto es para importar el componenete Equipo.vue */

export default {
  name: 'App',
  components: {
    Equipo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #000000;
  margin-top: 3rem;

}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  background-color: rgb(240, 255, 255);
}

.trifuerza_logo {
width: 2rem;
}

.cabecera {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 1rem;
}
</style>
