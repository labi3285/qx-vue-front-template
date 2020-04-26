<template>
  <div class="qx-card">
    <slot/>
  </div>
</template>

<script>
  export default {
    name: 'qx-card'
  }
</script>

<style lang="less">
  .qx-card {
    background-color: white;
    width: 100pt;
    height: 100pt;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    width: 40%;
    border-radius: 20px;
  }
  .qx-card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
</style>
