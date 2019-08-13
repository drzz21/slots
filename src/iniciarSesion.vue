<template>
    <div class="container">
        <div class="jumbotron">
            <mostrarFormulario>
                <div slot="titulo">
                    <h3>Iniciar sesion</h3>
                </div>
                <div slot="elementos">
                    <div class="form-group">
                        <label for="correo">Correo electronico</label>
                        <input type="email" class="form-control" id="correo" placeholder="Escribe tu correo electronico">
                    </div>
                    <div class="form-group">
                        <label for="clave">Contraseña</label>
                        <input type="password" class="form-control" id="clave" placeholder="Escribe tu contraseña">
                    </div>
                </div>
                <div slot="boton">
                    <button class="btn btn-primary">Iniciar sesion</button>
                </div>
            </mostrarFormulario>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
            }
        }
    }
</script>


<style scoped>
  
</style>
