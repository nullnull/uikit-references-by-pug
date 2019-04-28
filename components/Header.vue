<template lang="pug">
header.uk-navbar-container.tm-navbar-container.uk-sticky.uk-sticky-fixed
  .uk-container.uk-container-expand
    nav.uk-navbar
      small.uk-navbar-left
        | ※headerはposition fixedで上に固定、コンテンツをpadding-topしてるだけ。
        br
        | ※中身はuk-navbar。こういう要素をnavbarと呼ぶ。
      .uk-navbar-right
        ul.uk-navbar-nav(class="uk-visible@m")
          li
            a hoge
          li
            a fuga
          li
            a hoge
</template>

<style lang="stylus" scoped>
.tm-navbar-container
  color rgba(255,255,255,0.8)
  position fixed
  top 0px
  width 100%
  height 80px
  a
    color: rgba(255,255,255,0.8) !important

.tm-navbar-container:not(.uk-navbar-transparent)
    background linear-gradient(to left, #28a5f5, #1e87f0) !important
</style>
