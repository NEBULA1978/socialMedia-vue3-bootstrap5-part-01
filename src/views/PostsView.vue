<template>
  <div class="about">
    <h1>This is an posts page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. ...</p>
    <div class="text-center">
      <TheButton class="btn btn-primary btn-lg">Click me</TheButton>
    </div>
  </div>
  <TemplateView/>
  <ArrayObjetosId/>
  <ArrayObjetos/>
  <ArrayColores/>
</template>
<script>
import TemplateView from '@/components/TemplateView.vue'; // Usando el alias @ para src
import ArrayObjetosId from '@/components/ArrayObjetosId.vue'; // Usando el alias @ para src
import ArrayObjetos from '@/components/ArrayObjetos.vue'; // Usando el alias @ para src
import ArrayColores from '@/components/ArrayColores.vue'; // Usando el alias @ para src

export default {
  components: {
    TemplateView,
    ArrayObjetosId,
    ArrayObjetos,
    ArrayColores
  }
}
</script>

<style>
/* Estilos para el componente AboutView si es necesario */
</style>
