<template>
  <div>
    <h1>{{ msg }}</h1>
    <v-btn color="primary" elevation="2">TEST</v-btn>
    <v-btn depressed color="error"> Error </v-btn>
    <TestComponent></TestComponent>
  </div>
</template>

<script setup lang="ts">
let msg = $ref('test');
msg = 'ABC';
</script>

<style scoped></style>
