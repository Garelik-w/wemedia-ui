<template>
  <div class="new-page" :style="`min-height: ${layoutMinHeight}px`">
    <h1>图文列表</h1>
  </div>
</template>

<script>
  export default {
    name: 'GraphicList',
    inject: ['layoutMinHeight'],
    data() {
      return {
        desc: '这是一个图文列表演示页面'
      }
    }
  }
</script>

<style scoped lang="less">
</style>