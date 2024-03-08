<template>
    <div>
        <h1>{{ msg }}</h1>
        <p>
            Vamos a hablar sobre los primeros conceptos de Vue
        </p>
    </div>
    
</template>
  
  <script>
  export default {
    name: 'Equipo',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>

  </style>
  