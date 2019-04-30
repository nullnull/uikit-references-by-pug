<template lang="pug">
pre
  code#code.language-pug
    include ./grid.txt
</template>

<script>

import Prism from '~/plugins/prism'

export default {
  data() {
    return {
      html: null
    }
  },
  mounted() {
    Prism.highlightAll()
  }
}
</script>
