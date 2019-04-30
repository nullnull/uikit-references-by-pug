<template lang="pug">
main
  div(uk-grid='')
    .uk-section(class="uk-width-1-2@m uk-width-1-1@s")
      .uk-container
        Grid
    .uk-section(class="uk-width-1-2@m uk-visible@m")
      .uk-container
        GridRaw
</template>

<script>
import Grid from "@/components/Grid"
import GridRaw from "@/components/GridRaw"

export default {
  components: {
    Grid,
    GridRaw
  },
  transition: {
    mode: 'out-in',
    enterActiveClass: 'uk-animation-slide-right-small',
    leaveActiveClass: 'uk-animation-slide-right-small uk-animation-reverse'
  }
}
</script>
