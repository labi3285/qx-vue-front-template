<template>
  <div class="qx-scroll-container">
    <slot/>
  </div>
</template>

<script>
  export default {
    name: 'qx-scroll-container'
  }
</script>

<style lang="less">
  .qx-scroll-container {
    margin: 0;
    padding: 0;
    /*display: -webkit-flex; !* Safari *!*/
    /*display: flex;*/
    /*flex-direction: column;*/
    /*flex-wrap: wrap;*/
    /*justify-content: left;// space-between;*/
  }
</style>
