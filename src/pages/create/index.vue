<template>
  <h2 class="red">일정등록하기</h2>
  <TodoFrom :editing="false"/>
</template>

<script>
import TodoFrom from "@/components/TodoForm.vue";
export default {
  components: {
    TodoFrom,
  },
};
</script>

<style scoped>
.red{
  color: red;
}
</style>
