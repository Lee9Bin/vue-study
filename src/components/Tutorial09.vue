<script setup>
import { ref, onMounted } from "vue";

const pElementRef = ref(null);
onMounted(() => {
  pElementRef.value.textContent = "마운트 완료";
});
</script>

<template>
  <div>
    <p ref="pElementRef">안녕</p>
  </div>
</template>

<style scoped></style>
