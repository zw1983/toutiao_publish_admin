<template>
  <!--单页面的绑定元素，id和main.js中$mount('#app')的id对应-->
  <div id="app">
    <!--加一个默认文字-->
    <h1>黑马头条内容发布系统</h1>
    <!--routerview 默认路由入口-->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">

</style>
