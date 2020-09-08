<template>
  <div id="app">
<!--    <router-link to="/index">首页</router-link>-->
    <first></first>
    <second></second>
    <hr>
    <router-view></router-view>
  </div>
</template>

<script>
  import First from "./components/First";
  import second from "./components/second";
export default {
  name: 'App',
  components: {
    first: First,
    second: second,
  }
}
</script>

<style>

</style>
