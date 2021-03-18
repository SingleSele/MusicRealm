<template>
  <div class="nav-bar">
    <div id="nav-icon">--图标--</div>
    <div class="nav-bar-item" v-for="item in data().navItems" :key="item.key" :path="item.keyPath">
      <div>{{item.key}}</div>
    </div>
    <div id="search-bar">-----------------搜索框------------</div>
    <div id="user-icon">登录/注册</div>
  </div>
</template>

<script>
  export default {
    name: "Header",
    data(){
      return {
        data(){
          return {
            navItems: [
              {key: "音乐史", keyPath: ""},
              {key: "作词", keyPath: ""},
              {key: "作曲", keyPath: ""},
              {key: "混音", keyPath: ""},
              {key: "乐器", keyPath: ""},
              {key: "软件", keyPath: ""},
              {key: "音源", keyPath: ""},
              {key: "采样包", keyPath: ""},
            ]
          }
        }
      }
    },
    methods: {

    }
  }
</script>

<style scoped>
  .nav-bar{
    position: absolute;
    top: 0px;
    bottom: 0px;
    left: 0px;
    right: 0px;
    display: flex;
    flex-direction: row;
    border-bottom: 2px white solid;
  }
  .nav-bar > div{
    display: flex;
    border: 1px blue solid;
    height: 70px;
    color: white;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    font-size: small;
  }
  .nav-bar-item{
    width: 50px;
  }
  #nav-icon{
    width: 100px;
    margin-left: 30px;
    margin-right: 30px;
  }
  #search-bar{
    width: 400px;
  }
  #user-icon{
    position: absolute;
    right: 0px;
    width: 120px;
    margin-right: 40px;
  }
</style>