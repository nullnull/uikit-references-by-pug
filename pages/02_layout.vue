<template lang="pug">
  main
    h1 Card
    .uk-grid-match(class='uk-child-width-1-1@s uk-child-width-1-2@m', uk-grid='')
      div
        .uk-card.uk-card-hover.uk-card-body
          h3.uk-card-title Card
          a(href='https://getuikit.com/docs/card' target='blank')
            | link
          p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h3.uk-card-title Default
          p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      div
        .uk-card.uk-card-primary.uk-card-hover.uk-card-body.uk-light
          h3.uk-card-title Primary
          p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      div
        .uk-card.uk-card-secondary.uk-card-hover.uk-card-body.uk-light
          h3.uk-card-title Secondary
          p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
    h1 Align
    h3 Image Align
    .uk-panel
      img.uk-align-left.uk-margin-remove-adjacent(src='~/assets/images/light.jpg', width='225', height='150', alt='Example image')
      p
        | 画像を左に寄せつつ、適度に余白をつけたいときは
        code uk-align-left
        code uk-margin-remove-adjacent
        | を使う。
      p
        | Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    .uk-margin-large
    .uk-panel
      img.uk-align-center.uk-margin-remove-adjacent(class='uk-align-right@m', src='~/assets/images/light.jpg', width='225', height='150', alt='Example image')
      p
        | このalignもレスポンシブ対応できる。
        code uk-align-right@m
        | とすれば、mのときだけ適用される。スマホではcenter、PCでright/leftで使うのが良さそう。
      p
        | Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    h1 Background
    p
      code .uk-background-default
      | などをつけるだけで、背景色がつく。
    .uk-text-center(class='uk-child-width-1-2@s', uk-grid='')
      div
        .uk-background-default.uk-padding.uk-panel
          p.uk-h4 Default
      div
        .uk-background-muted.uk-padding.uk-panel
          p.uk-h4 Muted
      div
        .uk-background-primary.uk-light.uk-padding.uk-panel
          p.uk-h4 Primary
      div
        .uk-background-secondary.uk-light.uk-padding.uk-panel
          p.uk-h4 Secondary
    p
      | 背景画像を使うときは、cssでbackground-imageを指定しつつ、
      code .uk-background-cover
      code .uk-background-contain
      | を使う。
    .uk-light(class='uk-child-width-1-2@s', uk-grid='')
      div
        .uk-background-cover.uk-height-medium.uk-panel.uk-flex.uk-flex-center.uk-flex-middle(style='background-image: url(/_nuxt/assets/images/light.jpg);')
          p.uk-h4 Cover
      div
        .uk-background-contain.uk-background-muted.uk-height-medium.uk-panel.uk-flex.uk-flex-center.uk-flex-middle(style='background-image: url(/_nuxt/assets/images/light.jpg);')
          p.uk-h4 Contain




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
