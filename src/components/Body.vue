<template lang="pug">
.body
  .body__content
    .body__content__title Digital Product Manager
    .body__content__subtitle Product Manager
    .body__content__elem Create a unique illustration for a website, application, or presentation
    .body__content__button GET STARTED
  .body__image
    img(src='@/assets/images/05.png')
</template>

<script>
export default {
  name: "body",
};
</script>

<style lang="stylus" scoped>
.body
  display grid
  height 100%
  grid-template-columns 55% 45%
  &__content
    display flex
    flex-direction column
    align-items flex-start
    justify-content center
    margin 0em 3em

    &__title
      font-size 4.5em
      font-family SFBlack
      text-align initial
      padding-bottom 0.5em
      margin-right 2em
      @media(max-width 768px)
        display none
    &__subtitle
      display none
    &__elem
      font-size 1.25em
      font-family SFRegular
      padding-bottom 2em
      margin-right 25em
      text-align initial

    &__button
      padding-top 2em
      margin 0em
      border-radius 2.625em
      background-color #FF7F66
      color black
      padding 1em 1.5em
      font-family SFMedium
      font-size  1.3em
  &__image
    padding-top 2em
.body
  @media(max-width 768px)
    display flex
    flex-direction column-reverse
img
  @media(max-width 768px)
    width 24em
    height 24em
    padding-left 2em
    padding-top 2em
.body__content
  @media(max-width 768px)
    display flex
    flex-direction column
    justify-content center
    align-items center

.body__content__subtitle
  @media(max-width 768px)
    display flex
    font-size 2.25em
    font-family SFBold
    padding-top 0.8em
.body__content__elem
  @media(max-width 768px)
    justify-content center
    align-items center
    margin 0
    text-align center
    padding-top 1em
.body__content__button
  @media(max-width 768px)
    padding 0.5em 2em
</style>
