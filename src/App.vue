<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <Layout></Layout>
      <p>
        If Element is successfully added to this project, you'll see an
        <code v-text="'<el-button>'"></code>
        below
      </p>
      <el-button>el-button</el-button>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Layout from "./components/Layout.vue";

export default {
  name: 'app',
  components: {
    HelloWorld,
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
