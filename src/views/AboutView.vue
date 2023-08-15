<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. ...</p>
    <div class="text-center">
      <TheButton class="btn btn-primary btn-lg">Click me</TheButton>
    </div>
  </div>
  <ArrayColores/>
</template>

<script>
// Importa el componente TheButton desde su archivo correspondiente
// import TheButton from '../components/TheButton.vue';
import TheButton from '@/components/TheButton.vue'; // Usando el alias @ para src
import ArrayColores from '@/components/ArrayColores.vue'; // Usando el alias @ para src


export default {
  components: {
    TheButton,
    ArrayColores
  }
}
</script>

<style>
/* Estilos para el componente AboutView si es necesario */
</style>
