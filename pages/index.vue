<template lang="pug">
.uk-section
  .uk-container
    .uk-grid-match(class='uk-child-width-1-1@s uk-child-width-1-2@m', uk-grid='')
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Accordion
          a(href='https://getuikit.com/docs/accordion' target='blank')
            | link
          ul(uk-accordion='')
            li.uk-open
              a.uk-accordion-title(href='#') Item 1
              .uk-accordion-content
                p
                  | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            li
              a.uk-accordion-title(href='#') Item 2
              .uk-accordion-content
                p
                  | Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor reprehenderit.
            li
              a.uk-accordion-title(href='#') Item 3
              .uk-accordion-content
                p
                  | Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat proident.

      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Alert
          a(href='https://getuikit.com/docs/alert' target='blank')
            | link
          .uk-alert こんな感じのエリアのこと
          div.uk-alert-danger(uk-alert='')
            a.uk-alert-close(uk-close='')
            h3 Notice!!
            p
              code uk-alert-danger
              | などで色変更。
              br
              | aタグに
              code uk-alert-close
              | クラスで削除ボタン。
              code uk-close
              | をつければ罰印が作れる
          p
            | アニメーション関連も変更可能。
            code duration
            | など。
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Animation
          a(href='https://getuikit.com/docs/animation' target='blank')
            | link
          p
            | アニメーションは本家参照

      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Badge
          a(href='https://getuikit.com/docs/badge' target='blank')
            | link
          p
            span.uk-badge 100
          p
            | これ以外に説明がなかったw
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Base
          a(href='https://getuikit.com/docs/base' target='blank')
            | link
          h3 headingについて
          p
            code .uk-h1
            | などを使うと、その大きさに変化する。例えば、以下はh1タグで宣言しているが、h5と同じ大きさになる。
          h1.uk-h5
            | ここはh5
          h3 blockquote
          blockquote(cite='#')
            p.uk-margin-small-bottom
              | The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a footer or cite element.
            footer
              | Someone famous in
              cite
                a(href='#') Source Title
          h3 code
          pre
            code
              | print "hoge"
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Breadcrumb
          a(href='https://getuikit.com/docs/breadcrumb' target='blank')
            | link
          ul.uk-breadcrumb
            li
              a(href='') hoge
            li
              a(href='') fuga
            li
              span geho
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Button
          a(href='https://getuikit.com/docs/button' target='blank')
            | link
          p
            code uk-button
            | と
            code uk-button-default
            | /
            code uk-button-primary
            | をaタグかbuttonタグにつければ良い
          p(uk-margin='')
            a.uk-button.uk-button-default(href='#') Link
            button.uk-button.uk-button-default Default
            button.uk-button.uk-button-default(disabled='') Disabled
            button.uk-button.uk-button-primary Primary
            button.uk-button.uk-button-secondary Secondary
            button.uk-button.uk-button-danger Danger
            button.uk-button.uk-button-text Text
            button.uk-button.uk-button-link Link
            button.uk-button.uk-button-default.uk-button-small small
            button.uk-button.uk-button-default.uk-button-large large
            .uk-button-group
              button.uk-button.uk-button-secondary Button
              button.uk-button.uk-button-secondary Button
              button.uk-button.uk-button-secondary Button


      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Close
          a(href='https://getuikit.com/docs/close' target='blank')
            | link
          p
            | a,buttonにuk-close属性をつければ閉じボタンになる
          button.uk-close-large(type='button', uk-close='')
          p ドロップボタンなどでも同じく
          .uk-inline
            button.uk-button.uk-button-default(type='button') Click
            div(uk-drop='mode: click')
              .uk-card.uk-card-body.uk-card-default
                button.uk-drop-close(type='button', uk-close='')
                p
                  | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.

      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Description List
          a(href='https://getuikit.com/docs/description-list' target='blank')
            | link
          dl.uk-description-list.uk-description-list-divider
            dt Description term
            dd Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            dt Description term
            dd
              | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            dt Description term
            dd
              | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Divider
          a(href='https://getuikit.com/docs/divider' target='blank')
            | link
          hr
          hr.uk-divider-icon
          hr.uk-divider-small
          hr.uk-divider-vertical
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Animation
          a(href='https://getuikit.com/docs/animation' target='blank')
            | link
          p
            | アニメーションは本家参照
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Animation
          a(href='https://getuikit.com/docs/animation' target='blank')
            | link
          p
            | アニメーションは本家参照
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Animation
          a(href='https://getuikit.com/docs/animation' target='blank')
            | link
          p
            | アニメーションは本家参照
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Animation
          a(href='https://getuikit.com/docs/animation' target='blank')
            | link
          p
            | アニメーションは本家参照
      div
        .uk-card.uk-card-default.uk-card-hover.uk-card-body
          h1 Animation
          a(href='https://getuikit.com/docs/animation' target='blank')
            | link
          p
            | アニメーションは本家参照




</template>

<script>
export default {
  transition: {
    mode: 'out-in',
    enterActiveClass: 'uk-animation-slide-left-small',
    leaveActiveClass: 'uk-animation-slide-left-small uk-animation-reverse'
  }
}
</script>
