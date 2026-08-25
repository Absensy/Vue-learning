<template>
<h3>{{ info }}</h3>
<p> This is a paragraph </p>
</template>

<style scoped>
h3 {
  color: red;
  font-weight: lighter;
}
p {
  color: blue;
  font-weight: bold;
}
</style>

<script setup lang="ts">
const info = "Title"
</script>
