<template>
  <div>
    <h1>明白</h1>
    <h2>十九届</h2>
    <h2 v-for="i in list">{{ i }}</h2>
  </div>
</template>
<script setup lang="ts">
import { ref } from "vue";
let list = ref([1, 2, 3, 4, 5, 6]);
let fn = <N>(a: N): N => {
  return a;
};
console.log(fn("hh"));
</script>
