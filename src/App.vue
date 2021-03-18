<template>
  <div id="app">
      <Layout></Layout>
  </div>
</template>

<script>
import Layout from "./components/Layout.vue";

export default {
  name: 'app',
  components: {
    Layout,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  position: absolute;
  right: 0px;
  top: 0px;
  left: 0px;
  bottom: 0px;
  background-image: url("./images/example.png");
  background-repeat: no-repeat;
  background-size:100% 100%;
}
</style>
