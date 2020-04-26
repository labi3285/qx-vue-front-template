<template>
  <img ref="img" class="qx-icon" aria-hidden="true"/>
</template>

<script>
  export default {
    name: 'qx-icon',
    props: {
      path: {
        type: String,
        required: false
      },
      url: {
        type: String,
        required: false
      }
    },
    mounted () {
      if (this.$props.path) {
        this.$refs.img.src = require('@/' + this.$props.path)
      } else if (this.$props.url) {
        this.$refs.img.src = this.$props.url
      }
    }
  }
</script>

<style lang="less">
  .qx-icon {
    touch-action: pan-y;
    background-color: blue;
  }
</style>
