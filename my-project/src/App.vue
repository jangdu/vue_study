<template>
  <div>
    <TodoHeader/>
    <div class="wrap">
      <TodoMenu/>
      <TodoContent/>
    </div>
  </div>
</template>

<script>
import TodoHeader from "./components/TodoHeader";
import TodoMenu from "./components/TodoMenu";
import TodoContent from "@/components/TodoContent";

export default {
  name: "app",
  components: {
    // 컴포넌트이름 여러단어...?
    TodoHeader,
    TodoMenu,
    TodoContent
  }
};
</script>

<style scoped>
.wrap {
  display: flex;
}
</style>
