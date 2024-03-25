<script setup>
import {ref} from 'vue'

const titulo = ref('Título')
</script>

<template>
  <h1>{{ titulo }}</h1>
  <div class="contanier">
    <div class="formulario">
      <h2>Formulário</h2>
      <imput type="text" v-model="titulo"/>
    </div>
    <div class="resultado">
      <h2>Resultado</h2>
    </div>
  </div>
</template>

<style scoped>

.contanier{
display: flex;
flex-direction: row;
justify-content: center;
gap: 1.5rom;
width: 100w;

}
.formulario,
.resultado {
  background-color:black;
  width: 45%;
  border-radius: 10px;
  padding: 10px;
}

.formulario{
  background-color:crimson;
}

.resultado{
  background-color:bisque;
}
</style>