<template>
  <div class="header">城市选择
    <router-link to='/'>
      <div class="iconfont header-back" >&#xe624;</div>
    </router-link>
  </div>
</template>
<script>
export default {
  name: 'CityHeader'
}
</script>
<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.header{
  overflow: hidden
  height: $headerHeight
  line-height: $headerHeight
  text-align:center
  color:#fff
  background: $bgColor
  font-size :1.3rem
}
.header-back{
  position :absolute
  top:0
  left :.4rem
  width :1.2rem
  text-align :center
  font-size: 1.4rem
  color :#fff
}
</style>
