<template>
  <div class="wrapper">

    <div>
      <img style="width:100%;" src="../../assets/img/pic_banner@2x.png">
    </div>

    <qx-icon path="assets/img/icon/icon_shanghu_one.png"></qx-icon>
    <qx-icon url="https://img.yzcdn.cn/vant/logo.png" width="50pt"></qx-icon>

    <qx-label text="label"></qx-label>

    <qx-items-menu>
      <qx-icon-label-button class="my-button" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>

      <qx-icon-label-button class="my-button" title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
      <qx-icon-label-button title="菜单" iconPath="assets/img/icon/icon_shanghu_one.png"></qx-icon-label-button>
    </qx-items-menu>

    <!--<qx-icon-label-button title="xxx" iconUrl="https://img.yzcdn.cn/vant/logo.png"></qx-icon-label-button>-->
    <!--<qx-icon-label-button title="xxx" iconUrl="https://img.yzcdn.cn/vant/logo.png"></qx-icon-label-button>-->
    <!--<qx-icon-label-button title="xxx" iconUrl="https://img.yzcdn.cn/vant/logo.png"></qx-icon-label-button>-->

    <!--<x-button>submit</x-button>-->
    <!--<x-button type="primary">primary</x-button>-->
    <!--<x-button type="warn">Delete</x-button>-->

    <!--<divider>link</divider>-->
    <!--<x-button type="default" show-loading>submit</x-button>-->
    <!--<x-button type="primary" show-loading>submit</x-button>-->
    <!--<x-button type="warn" show-loading>submit</x-button>-->
  </div>
</template>

<script>
  import qxIcon from '@/components/qx-icon'
  import qxLabel from '@/components/qx-label'
  import qxIconLabelButton from '@/components/qx-icon-label-button'
  import qxItemsMenu from '@/components/qx-items-menu'

  import store from '@/store/index'
  import { mapActions } from 'vuex'
  import { XButton, Divider } from 'vux'

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
      qxLabel,
      qxIcon,
      qxIconLabelButton,
      qxItemsMenu,
      XButton,
      Divider
    },
    store
  }
</script>

<style>
  .container {
    margin: 0px auto;
    height: 100vh;
    width: 80%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .content {
    background-color: #ffffff;
    margin: 15px;
    border-radius: 8px;
  }

  .my-button .qx-icon {
    background-color: #ce3c39 !important;
  }

</style>

