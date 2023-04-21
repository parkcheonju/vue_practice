<template>
  <h1>일정내용</h1>
</template>

<script>
import { useRoute } from "vue-router";
export default {
  setup() {
    const route = useRoute();
    console.log("id🙄",route.params.id);
  },
};
</script>

<style></style>
