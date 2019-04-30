<template lang="pug">
main
  div(uk-grid='')
    .uk-section.scroll(class="uk-width-1-2@m uk-width-1-1@s")
      .uk-container.uk-container-large
        include ../templates/layout.pug
    .scroll(class="uk-width-1-2@m uk-visible@m")
      pre
        code#code.language-pug
          include ../templates/layout.txt
</template>

<script>
import Prism from '~/plugins/prism'

export default {
  transition: {
    mode: 'out-in',
    enterActiveClass: 'uk-animation-slide-right-small',
    leaveActiveClass: 'uk-animation-slide-right-small uk-animation-reverse'
  },
  mounted() {
    Prism.highlightAll()
  }
}
</script>

<style lang="stylus" scoped>
.scroll
  overflow scroll
  height calc(100vh - 80px)
pre
  margin 0
</style>
