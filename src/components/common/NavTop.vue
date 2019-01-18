<template>
  <div class="nav-top">
      
    <el-row :gutter="20" class="app-nav-top">
        <el-col :span="22" :offset="1">
            <el-col :span="12" >
                <ul class="nav-top-list-left">
                    <li>
                    <router-link to="/login">登陆</router-link>
                    </li>
                    <li>
                    <router-link to="/reg">注册</router-link>
                    </li>
                    <li>
                    <span>余额:</span>
                    <router-link to="/reg">0.0</router-link>
                    </li>
                    <li>
                    <span>积分:</span>
                    <router-link to="/reg">1.1</router-link>
                    </li>
                </ul>
            </el-col>

            <el-col :span="12" >
                <ul class="nav-top-list-right">
                    <li>
                    <router-link to="/quit">退出</router-link>
                    </li>
                    <li>
                    <router-link to="/app">
                        <i class="el-icon-sold-out"></i>
                        APP
                    </router-link>
                    </li>
                    <li>
                    <router-link to="/setting">
                        <i class="el-icon-setting"></i>
                        设置
                    </router-link>
                    </li>
                    <li>
                    <router-link to="/message">
                        <i class="el-icon-message"></i>
                        消息
                    </router-link>
                    </li>
                    <li>
                    <router-link to="/out">提现</router-link>
                    </li>
                    <li>
                    <router-link to="/in">充值</router-link>
                    </li>
                </ul>
            </el-col>
        </el-col>
    </el-row>

  </div>
</template>

<script>
export default {
}
</script>

<style scoped lang="less">
// nav-top
.app-nav-top{
  height: 40px;
  line-height: 40px;
  color: #ffffff;
  border-bottom: 1px solid #151515;
  background: -webkit-gradient(linear, left top, left bottom, from(#2f2f2f), to(#151515));
  background: linear-gradient(#2f2f2f, #151515);
  text-align: left;

  // list
  & .nav-top-list-left{
    list-style: none;
    padding: 0;
    height: 100%;
    line-height: 100%;

    & li{
      float: left;
      & a{
        padding: 5px 10px;
        // border: 1px solid #ccc;
      }
    }
  }

  & .nav-top-list-right{
    list-style: none;
    padding: 0;
    height: 100%;
    line-height: 100%;

    & li{
      float: right;
      & a{
        padding: 5px;
        // border: 1px solid #ccc;
      }
    }
  }

}
</style>
