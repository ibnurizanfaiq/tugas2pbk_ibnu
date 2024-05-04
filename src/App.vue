<template>
<div class=" main">
  <h1 >IBNU RIZAN FAIQ</h1>

  <input type="text" placeholder="masukan inputan" v-model="input" class="form-control">
  <p :class='judul' >{{ input }}</p>
</div>

</template>

<script setup>
import { ref } from 'vue';

const judul = ref('title')
const input = ref("")
</script>

<style scoped>
.title{
  color: rgb(222, 166, 25);
  text-transform: uppercase;
}
h1{
  color: rgb(222, 166, 25);
}
.main{
  margin-top: 100%;
}
</style>