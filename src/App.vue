<template>
  <div id="app">

    <el-header style="padding: 0;margin: 0;height:auto;">
      <app-head></app-head>
    </el-header>

    <!-- <div id="nav">
      <router-link to="/">首页</router-link> |
      <router-link to="/about">关于</router-link>
    </div> -->

    <router-view/>

  </div>
</template>

<style lang="less">
html,
body,
#app{
  padding: 0;
  margin: 0;
  width:100%;
  height: 100%;
  font-size: 14px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

a {
  color: #ffffff;
  text-decoration:none;
  
  &.router-link-exact-active {
    color: #42b983;
  }
}

.el-header{
  padding: 0;margin: 0;
}

.pull-left{
  float: left;
}

.pull-right{
  float: right;
}
</style>
