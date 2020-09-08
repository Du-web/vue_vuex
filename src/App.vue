<template>
  <div id="app">
<!--    <router-link to="/index">首页</router-link>-->
    <first></first>
    <hr>
    <router-view></router-view>
  </div>
</template>

<script>
  import First from "./components/First";
export default {
  name: 'App',
  components: {
    first: First,
  }
}
</script>

<style>

</style>
