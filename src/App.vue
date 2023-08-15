<template>
  <NavComp />
  <router-view/>
  <TheButton/>
  <Contador/>
  
</template>

<script>
import NavComp from "@/components/NavComp.vue"
import Contador from "@/components/Contador.vue"
export default {
  name: "App",
  components: {
    NavComp,
    Contador
    
  }
}
</script>

<style>
#app {
  color: #2c3e50;
}


</style>
