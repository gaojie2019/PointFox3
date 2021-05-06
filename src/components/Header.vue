<template>
  <div id="headerWrapper">
    <div id="headerTitle">
      <span>{{ message }}</span>
    </div>
    <div id="headerFunction">
      <router-link to="/register">
       <el-button class="funcBtn">用户注册</el-button>
      </router-link>
      <router-link to="/login">
       <el-button class="funcBtn">系统登录</el-button>
      </router-link>

       <router-link to="/work">
       <el-button class="funcBtn">工作中心</el-button>
       </router-link>

       <router-link to="/Reader">
       <el-button class="funcBtn">读者信息</el-button>
       </router-link>

       <router-link to="/Book">
       <el-button class="funcBtn">图书信息</el-button>
       </router-link>
       <router-link to="/cnnode">
       <el-button class="funcBtn">node论坛</el-button>
       </router-link>

      
        
        
        
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "江西软件大学-图书管理系统",
    };
  },
};
</script>

<style>
#headerTitle {
  /* background-color: blue; */
  display: inline-block;
  color: white;
  font-size: 20px;
  font-weight: bolder;
  height: 60px;
  line-height: 60px;
}
#headerFunction {
  /* background-color: purple; */
  display: inline-block;
  float: right;
  height: 60px;
  padding-top: 10.2px;
}
.funcBtn {
  background-color: #0a9588 !important;
  border-color: #0a9588 !important;
  color: white !important;
}
</style>