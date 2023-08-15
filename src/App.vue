<template>
  <NavComp />
  <router-view/>
  <TheButton/>
  
</template>

<script>
import NavComp from "@/components/NavComp.vue"
export default {
  name: "App",
  components: {
    NavComp
    
  }
}
</script>

<style>
#app {
  color: #2c3e50;
}


</style>
