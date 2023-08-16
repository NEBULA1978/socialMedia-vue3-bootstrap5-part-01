<template>
  <div>
    <h1>Directivas</h1>
   
    <VBindVShowIfElseIf />
    <VBind />
    <VForFrutas />
    <!-- <VForVIf />
    <ComputedFuncion />
    <Computed />
    <Contador /> -->
    <!-- ...otros elementos del template... -->
  </div>
</template>

<script>
// Importando componentes faltantes

import VBindVShowIfElseIf from '@/components/V-bind-V-show-If-ElseIf.vue';
import VBind from '@/components/Vbind.vue';
import VForFrutas from '@/components/V-for-Frutas.vue';

// Me añade un navbar mas
// import VForVIf from '@/components/V-for-V-If.vue';
// import ComputedFuncion from '@/components/ComputedFuncion.vue';
// import Computed from '@/components/Computed.vue';
// import Contador from '@/components/Contador.vue';

export default {
  components: {
  
    VBindVShowIfElseIf,
    VBind,
    VForFrutas,
    // VForVIf,
    // ComputedFuncion,
    // Computed,
    // Contador
  },
  // ...otras propiedades y métodos...
}
</script>
