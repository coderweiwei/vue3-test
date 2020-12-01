<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>上面是父组件传递过来的属性</p>
    <h1>测试页面 哈啊哈哈哈</h1>
    <h2>绩效考核</h2>
    <h2>测试项目</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

</style>
