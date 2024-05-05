<script setup>
import { ref } from "vue";

const count = ref(0);

function add() {
  count.value += 1;
}
</script>

<template>
  <div>
    <button @click="add">숫자 세기: {{ count }}</button>
  </div>
</template>

<style scoped></style>
