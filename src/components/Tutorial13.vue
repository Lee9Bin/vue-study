<script setup>
import { ref } from "vue";
import ChildComp3 from "./ChildComp3.vue";

const childMsg = ref("자식 컴포넌트로부터 아직 메시지를 받지 못했어요!");
</script>

<template>
  <div>
    <ChildComp3 @response="(msg) => (childMsg = msg)" />
    <p>{{ childMsg }}</p>
  </div>
</template>

<style scoped></style>
