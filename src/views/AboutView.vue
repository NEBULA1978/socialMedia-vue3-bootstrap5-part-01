<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. ...</p>
    <div class="text-center">
      <TheButton class="btn btn-primary btn-lg">Click me</TheButton>
    </div>
  </div>
</template>

<script>
// Importa el componente TheButton desde su archivo correspondiente
import TheButton from './TheButton.vue';

export default {
  components: {
    TheButton
  }
}
</script>

<style>
/* Estilos para el componente AboutView si es necesario */
</style>
