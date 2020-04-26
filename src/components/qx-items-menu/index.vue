<template>
  <div class="qx-items-menu">
    <slot/>
  </div>
</template>

<script>
  export default {
    name: 'qx-items-menu'
  }
</script>

<style lang="less">
  .qx-items-menu {
    width: 100%;
    background-color: yellow;
    display: -webkit-flex; /* Safari */
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
    align-items: center;
    /*padding: 10pt;*/
  }

</style>
