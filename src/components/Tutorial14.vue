<script setup>
import { ref } from "vue";
import ChildComp4 from "./ChildComp4.vue";

const msg = ref("Vue는 개발자에게 정말 유용하죠! 🎁");
</script>

<template>
  <div>
    <ChildComp4>부모로부터: {{ msg }}</ChildComp4>
  </div>
</template>

<style scoped></style>
