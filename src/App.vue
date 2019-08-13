<template>
  <div class="container">
    <div class="jumbotron">
      <button class="btn btn-primary" @click="componenteSeleccionado='iniciarSesion'">Iniciar sesión</button>
      <button class="btn btn-danger" @click="componenteSeleccionado='cambiarClave'">Cambiar contraseña</button>
    </div>
  </div>
</template>

<script>
  import MostrarFormulario from './mostrarFormulario.vue'
  import IniciarSesion from './iniciarSesion.vue/'
  import CambiarClave from './cambiarClave.vue/'

  export default {
    components: {
      iniciarSesion:IniciarSesion
      
    },
    data() {
      return{
        componenteSeleccionado:'iniciarSesion'
      }
    }
  }
</script>

<style scoped>
  h3 {
    color: green;
  }
</style>
