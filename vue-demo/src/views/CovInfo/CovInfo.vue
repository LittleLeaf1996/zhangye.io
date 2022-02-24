<template>
  <div class="info">
  <div class="title">病毒信息</div>
  <p>病毒信息：xxx</p>
  <p>病毒信息：xxx</p>
  <p>病毒信息：xxx</p>
  <p>病毒信息：xxx</p>
  </div>
</template>

<script>
export default {
  name: 'CovInfo'
}
</script>

<style lang="less" scope >
.info {
  padding:0.2rem;
  .title {
    border-left: 0.1rem solid rgb(20, 49, 128);
    padding-left:0.1rem;
    margin-bottom:0.2rem;
  }
  p{
    line-height: 0.4rem;
    color: #666;
  }
}
</style>
