<template>
  <div>
    first组件
    <button @click="add">按钮</button>
  </div>
</template>

<script>
    export default {
        name: "First",
      methods: {
          add(){
            this.commit('add_count')
          },
      }

    }
</script>

<style scoped>

</style>
