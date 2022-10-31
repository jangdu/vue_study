<template>
  <div>
    <Header/>
    <div>
      <Menu/>
      <Content/>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Menu from "@/components/Menu";
import Content from "@/components/Content";

export default {
  name: "app",
  components: { // 가져온 component 들을 등록합니다.
    Header,
    Menu,
    Content
  }
};
</script>

<style scoped>
h1 {
  color: blue;
}
</style>
