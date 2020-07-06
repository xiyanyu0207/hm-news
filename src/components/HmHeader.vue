<template>
  <div class="hm-header">
    <div class="back">
      <span class="iconfont iconjiantou2" @click="$router.go(-1)"></span>
    </div>
    <div class="content"><slot></slot></div>
    <div class="extra"></div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less">
.hm-header {
  display: flex;
  height: 40px;
  line-height: 40px;
  border-bottom: 1px solid #ccc;
  .back,
  .extra {
    width: 40px;
    text-align: center;
  }
  .content {
    flex: 1;
    font-size: 16px;
    text-align: center;
    font-weight: 700;
  }
}
</style>
