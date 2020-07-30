<template>
  <div>
    我是新导入的组件{{msg}}
    <el-radio v-model="radio" label="1">备选项1</el-radio>
    <el-radio v-model="radio" label="2">备选项2</el-radio>
  </div>
</template>

<script>
  export default {
    name: "Hello",
    data() {
      return {
        msg: 'Welcome to Your Vue.js App',
        radio: "2",
      }
    }
  }
</script>

<style scoped>

</style>
