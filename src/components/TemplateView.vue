<template>
  <h1>{{ texto }}</h1>
</template>

<style>
h1 {
  color: rebeccapurple;
}
</style>

<script>
export default {
  data() {
    return {
      texto: 'Hola VUE3 dinámico'
    };
  },
  components: {
    // No es necesario definir componentes aquí
  }
}
</script>
