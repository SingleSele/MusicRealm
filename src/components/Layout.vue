<template>
  <div>
  <div class="header">这是顶栏</div>
  <div class="navbar">这是左侧栏</div>
  <div class="main">主栏</div>
  </div>
</template>

<script>
export default {
name: "Layout"
}
</script>

<style scoped>
.header {
  position: absolute;
  line-height: 70px;
  top: 0px;
  left: 0px;
  right: 0px;
  background-color: rgba(255, 0, 0, 0.3);
}

.navbar {
  position: absolute;
  width: 320px;
  top: 70px;
  left: 0px;
  bottom: 0px;
  background-color: rgba(0, 255, 0, 0.3);
}

.main {
  position: absolute;
  top: 70px;
  left: 320px;
  bottom: 0px;
  right: 0px;
  padding: 10px;
  background-color: rgba(0, 0, 255, 0.3);
}
</style>