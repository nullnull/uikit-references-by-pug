<template lang="pug">
  main
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
