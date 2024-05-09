<template>
    <div class="new-page" :style="`min-height: ${layoutMinHeight}px`">
        <h1>视频设计器</h1>
    </div>
</template>

<script>
export default {
    name: 'NewPage',
    inject: ['layoutMinHeight'],
    data() {
        return {
            desc: '这是一个视频设计器演示页面'
        }
    }
}
</script>

<style scoped lang="less">
</style>