<template>
  <div>
    <div class="header">a</div>
    <div class="navbar">这是左侧栏</div>
    <div class="main"><test-article></test-article></div>
  </div>
</template>

<script>
  // import Header from "@/components/Header";
  import TestArticle from "@/views/TestArticle";

  export default {
    name: "Layout",
    components: {
      TestArticle
    }
  }
</script>

<style scoped>
.header {
  position: fixed;
  line-height: 70px;
  top: 0px;
  width: 100%;
  z-index: 100;
  background-color: rgba(255, 0, 0, 0.3);
}

.navbar {
  position: absolute;
  width: 320px;
  left: 0px;
  margin-top: 70px;
  background-color: rgba(0, 255, 0, 0.3);
}

.main {
  position: absolute;
  margin-top: 70px;
  margin-left: 320px;
  left: 0px;
  right: 0px;
  padding: 10px;
  background-color: rgba(0, 0, 255, 0.3);
}
</style>