<template>
  <div id="app">
    <router-view />
    <i class="iconfont iconlishi"></i>
    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less"></style>
