<template>
  <div class="qx-collection-container">
    <slot/>
  </div>
</template>

<script>
  export default {
    name: 'qx-collection-container'
  }
</script>

<style lang="less">
  .qx-collection-container {
    display: -webkit-flex; /* Safari */
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: left;
  }
</style>
