<template lang="pug">
  div
    Header
    Sidebar
    .tm-main
      nuxt
</template>

<script>
import Header from '@/components/Header'
import Sidebar from '@/components/Sidebar'

export default {
  components: {
    Header,
    Sidebar
  }
}
</script>

<style lang="stylus" scoped>
/* header, sidebarの高さと幅に合わせる */
.tm-main
  padding-top 80px
  @media screen and (min-width: 900px)
    padding-left 160px
</style>
