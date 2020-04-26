<template>

  <qx-scroll-container class="content">

    <qx-image class="head" path="assets/img/pic_denglu_beingjing.png"></qx-image>

    <qx-collection-container class="menu-container">
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button class="menu-item" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
    </qx-collection-container>

    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->
    <!--<p>xxxxxxxxx</p><br/>-->

  </qx-scroll-container>

</template>

<script>
  import qxImage from '@/components/qx-image'
  import qxIcon from '@/components/qx-icon'
  import qxLabel from '@/components/qx-label'
  import qxIconLabelButton from '@/components/qx-icon-label-button'
  import qxScrollContainer from '@/components/qx-scroll-container'

  import qxCollectionContainer from '@/components/qx-collection-container'
  import qxCard from '@/components/qx-card'

  import store from '@/store/index'
  import { mapActions } from 'vuex'

  export default {
    name: 'home',
    data () {
      return {
      }
    },
    methods: {
      ...mapActions(['loadPageConfig'])
    },
    components: {
      qxImage,
      qxLabel,
      qxIcon,
      qxIconLabelButton,
      qxCollectionContainer,
      qxScrollContainer,
      qxCard
    },
    store
  }
</script>

<style>
  .content {
    background-color: yellow;
    height: 100vh;
  }
  .head {
    width: 100%;
  }
  .menu-container {
    background-color: white;
    padding-top: 10pt;
    border-radius:15pt 15pt 0 0;
  }
  .menu-item {
    width: calc(100vw/4);
    height: calc(100vw/4);
  }
  .menu-item .qx-icon {
    width: 40pt;
    height: 40pt;
  }
  .menu-item .qx-label {
    margin-top: 5pt;
    color: #999999;
    font-size: 10pt;
  }

</style>

