<template>
  <div>
    <div class="breadcrumb_box">
      <el-breadcrumb separator="/">
        <el-breadcrumb-item :to="{ path: '/index' }">主页</el-breadcrumb-item>
        <el-breadcrumb-item>导航一</el-breadcrumb-item>
        <el-breadcrumb-item>{{$route.meta.title}}</el-breadcrumb-item>
      </el-breadcrumb>
    </div>
  </div>
</template>

<script>
export default {
  name: "One",
  data() {
    return {};
  },
  mounted() {
    console.log(111);
  }
};
</script>

<style lang="scss" scoped>
</style>