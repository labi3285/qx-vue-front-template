<template>
  <div class="qx-icon-title-button">
    <qx-icon :path="iconPath" :url="iconUrl"></qx-icon>
    <qx-label :text="title"></qx-label>
  </div>

</template>

<script>
  import qxIcon from '../qx-icon'
  import qxLabel from '../qx-label'

  export default {
    name: 'qx-icon-title-button',
    components: {
      qxLabel,
      qxIcon
    },
    props: {
      iconPath: {
        type: String,
        required: false
      },
      iconUrl: {
        type: String,
        required: false
      },
      title: {
        type: String,
        required: false
      }
    }
  }
</script>

<style lang="less">
  .qx-icon-title-button {
    display: -webkit-flex; /* Safari */
    display: inline-flex;
    flex-direction: column;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;

    padding: 5pt;
  }
  .qx-icon-title-button .qx-icon {
    width: 40pt;
    height: 40pt;
    background-color: green;

  }
  .qx-icon-title-button .qx-label {
    font-size: 12pt;
    color: #999999;
  }
</style>
