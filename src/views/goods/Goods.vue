<template>
  <div class="goods">
      <!-- 面包屑 -->
    <el-breadcrumb separator-class="el-icon-arrow-right">
      <el-breadcrumb-item :to="{ path: '/home' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>权限管理</el-breadcrumb-item>
      <el-breadcrumb-item>角色列表</el-breadcrumb-item>
    </el-breadcrumb>
    <!-- 卡片 -->
    <el-card class="box-card">
      <router-view></router-view>
    </el-card>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style lang='less' scoped>
</style>
