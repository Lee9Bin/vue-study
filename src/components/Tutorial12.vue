<script setup>
import { ref } from "vue";
import ChildComp2 from "./ChildComp2.vue";

const greeting = ref("부모 컴포넌트로부터 💌을 전달받았어요!");
</script>

<template>
  <div>
    <ChildComp2 :msg="greeting" />
  </div>
</template>

<style scoped></style>
