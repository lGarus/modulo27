<script setup>
let a = Number
let b =  Number

const calcula = function(a, b) {
  return a + b
}

</script>

<template>

  <input type="{{ a }}">
  <input type="{{ b }}">
  <h1>{{ calcula }}</h1>

</template>

<style scoped>

</style>
