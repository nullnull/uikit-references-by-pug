<template lang="pug">
  main
    h1 Fixed Background
    p これ面白いねw
    .uk-margin-large
    hr
    .uk-margin-large
    hr
    .uk-margin-large
    .uk-background-fixed.uk-background-center-center.uk-height-medium.uk-width-large(style='background-image: url(images/dark.jpg);')
    .uk-margin-large
    hr
    .uk-margin-large
    hr
    .uk-margin-large
    hr
    .uk-margin-large
    hr
    .uk-margin-large
    hr
    .uk-margin-large
    hr




</template>

<script>
export default {
  transition: {
    mode: 'out-in',
    enterActiveClass: 'uk-animation-slide-right-small',
    leaveActiveClass: 'uk-animation-slide-right-small uk-animation-reverse'
  }
}
</script>
