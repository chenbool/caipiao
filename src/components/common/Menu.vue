<template>
  <div class="menu">

    <el-col :span="22" :offset="1">
      <el-menu
        default-active="/"
        class="el-menu-demo"
        mode="horizontal"
        router>

        <el-menu-item index="/">首页</el-menu-item>
        <el-menu-item index="/2">彩票大厅</el-menu-item>
        <el-menu-item index="/3">彩票资讯</el-menu-item>
        <el-menu-item index="/4">开奖公告</el-menu-item>
        <el-menu-item index="/5">比分直播</el-menu-item>

        <!-- <el-submenu index="2">
          <template slot="title">我的工作台</template>
          <el-menu-item index="2-1">选项1</el-menu-item>
          <el-menu-item index="2-2">选项2</el-menu-item>
          <el-menu-item index="2-3">选项3</el-menu-item>
        </el-submenu> -->

        <el-menu-item index="/about">关于</el-menu-item>

      </el-menu>
    </el-col>
    
  </div>
</template>

<script>
export default {
  name: 'menus'
}
</script>

<style scoped lang="less">
.el-menu{
  & a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration:none;
  }
}

.el-menu-item{
  height: 40px;
  line-height: 40px;
  background: #ffffff;
}
</style>
