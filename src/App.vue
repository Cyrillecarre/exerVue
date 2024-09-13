<template>
  <h1>Bonjour  {{ firstName.toUpperCase() }}</h1>
</template>


<script setup>
const firstName = 'John';
</script>

<style>
h1 {
  color: red;
}
</style>