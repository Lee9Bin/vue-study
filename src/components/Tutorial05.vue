<script setup>
import { ref } from "vue";

const text = ref("");

function onInput(e) {
  text.value = e.target.value;
}
</script>

<template>
  <div>
    <!-- <input :value="text" @input="onInput" placeholder="여기에 입력하기" /> -->
    <input v-model="text" placeholder="여기에 입력하기" />
    <p>{{ text }}</p>
  </div>
</template>

<style scoped></style>
