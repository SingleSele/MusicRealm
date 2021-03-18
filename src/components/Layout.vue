<template>
  <div id="view">
    <div class="header"><Header></Header></div>
    <div class="side-bar">
      这<br/>是<br/>左<br/>侧<br/>栏<br/>这<br/>是<br/>左<br/>侧<br/>栏<br/>这<br/>是<br/>左<br/>侧<br/>栏<br/>这<br/>是<br/>左<br/>侧<br/>栏<br/>
    </div>
    <div class="side-bar-divider"></div>
    <div class="main"><test-article></test-article></div>
  </div>
</template>

<script>
  import Header from "@/components/Header";
  import TestArticle from "@/views/TestArticle";

  export default {
    name: "Layout",
    components: {
      Header,
      TestArticle
    }
  }
</script>

<style scoped>
.header {
  position: fixed;
  height: 70px;
  top: 0px;
  width: 100%;
  z-index: 100;
  background-color: rgba(255, 0, 0, 0.3);
}
.side-bar-divider{
  position: fixed;
  width: 0px;

  left: 318px;
  top:0px;
  bottom: 20px;
  margin-top: 90px;
  border: 1px red solid;
}
.side-bar {
  position: absolute;
  width: 318px;
  left: 0px;
  margin-top: 70px;
  background-color: rgba(0, 255, 0, 0.3);
  color: white;
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