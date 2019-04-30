<template lang="pug">
.tm-sidebar-left(class="uk-visible@m")
  nuxt-link(":to"="'/'")
    h3 Home
  ul.uk-nav.uk-nav-default.tm-nav
    li.uk-nav-header Main
    li
      nuxt-link(":to"="'/01_grid'")
        | 01 Grid
    li
      nuxt-link(":to"="'/02_layout'")
        | 02 Layout
    li
      nuxt-link(":to"="'/03_advance'")
        | 03 Advance
  .uk-margin
  small
    p
      | ※sidebarはposition fixedで左に固定、その分コンテンツをpadding-leftしているだけ。
    p
      | ※中身はuk-navで作成する。デフォルトだとただのリストだが、accordionが使えたりdivider使えたり、ナビゲーションとしての要素が色々使える。
</template>

<style lang="stylus" scoped>
.tm-sidebar-left
  position fixed
  top 80px
  bottom 0
  box-sizing border-box
  width 240px !important
  padding 40px 40px 60px 40px
  border-right 1px #e5e5e5 solid
  overflow auto
</style>
