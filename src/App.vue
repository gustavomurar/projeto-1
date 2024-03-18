<script setup>
 import { ref } from 'vue';

const nome = ref('');
</script>

<template>
  <h1>Formulário de inscrição:</h1>

  <div class="infos">
    <p>Nome: {{ nome }} </p>
  </div>
</template>

<style scoped>
.info {
  background-color: rgb(199, 0, 86);
  padding: 20px 30px;
  color: rgb(0, 191, 255);
  border-radius: 10px;
}

h1 {
  color: rgb(0, 0, 0);
  font-weight: bold;
  font-size: 1.5em;
}
</style>
