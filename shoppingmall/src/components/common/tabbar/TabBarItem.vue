<template>
  <div css="tab-bar-item">
    <img src="" />
    <div>首页</div>
  </div>
</template>

<script>
  export default {
    name:'TabBarItem'
  }

</script>
<style scoped>
  .tab-bar-item{
    flex: 1;
    text-align: center;
    height: 49px;
    font-size: 14px;
  } 
  .tab-bar-item img {
    width: 24px;
    height: 24px;
    margin-top: 3px;
    vertical-align: middle;
    margin-bottom: 2px;
  }

</style>