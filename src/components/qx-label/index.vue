<template>
  <p class="qx-label">{{ text }}</p>
</template>

<script>
  export default {
    name: 'qx-label',
    props: {
      text: {
        type: String,
        required: false
      }
    }
  }
</script>

<style>
  .qx-label {
    touch-action: pan-y;
  }
</style>
