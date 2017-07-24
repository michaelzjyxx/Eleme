<template>
  <div id="app">
    <vheader></vheader>
    <div class="tab">
      <div class="tapItem">商品</div>
      <div class="tapItem">评论</div>
      <div class="tapItem">商家</div>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
  import Vheader from './components/Header/Header'

  export default {
    name: 'app',
    components: {
      Vheader
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  #app
    .tab
      display: flex
      width: 100%
      height: 40px
      line-height: 40px
      .tapItem
        flex: 1
        text-align: center
</style>
