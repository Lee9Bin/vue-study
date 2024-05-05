<script setup>
import JSConfetti from "js-confetti";

const confetti = new JSConfetti();

function showConfetti() {
  confetti.addConfetti();
}

showConfetti();
</script>

<template>
  <div><h1 @click="showConfetti">🎉 축하합니다!</h1></div>
</template>

<style scoped>
h1 {
  text-align: center;
  cursor: pointer;
  margin-top: 3em;
}
</style>
