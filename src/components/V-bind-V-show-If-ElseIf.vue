<!-- Interpolacion de texto -->

<script setup>
const name = 'Vue Dinamico';
const stylecolor = "color:blue";
const arrayColores = ["blue", "red", "peru"]
// Sino defino me sale inactivo
const activo = true
// const activo = false

</script>

<template>
  <h1>Hola {{ name.toUpperCase() }}</h1>

  <!-- Asi va bien -->
  <!-- <h2 style="color:blue">Soy azul</h2> -->

  <!-- Asi no va bien -->
  <!-- <h2 style="{{ stylecolor }}">Soy azul</h2> -->

  <!-- ASi podemos poner la variable del color -->
  <h2 v-bind:style="stylecolor">Soy azul</h2>
  <!-- Atajo de arriba de v-bind -->
  <h2 :style="stylecolor">Soy azul</h2>

  <!-- Cambia el color del texto usando un array de colores -->
  <h2 :style="`color: ${arrayColores[0]}`">Soy de color azul</h2>
  <h2 :style="`color: ${arrayColores[1]}`">Soy de color rojo</h2>
  <h2 :style="`color: ${arrayColores[2]}`">Soy de color peru</h2>

  <!-- Muestra el contenido del arrayColores -->
  <h2>{{ arrayColores }}</h2>

  <!-- Operador ternario para mostrar texto según el valor de 'activo' -->
  <h2>{{ activo ? "Estoy activo" : "Estoy inactivo" }}</h2>

  <!-- Directivas v-if, v-else-if y v-else -->
  <h2 v-if="activo">Estoy activo</h2>
  <h2 v-else>Estoy inactivo</h2>

  <!-- Directiva v-show para mostrar u ocultar contenido -->
  <h2 v-show="activo">Estoy activo v-show</h2>
</template>

<style>
h1 {
  color: rebeccapurple;
}
</style>
