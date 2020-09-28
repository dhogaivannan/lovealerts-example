<template lang="pug">
.header
  .header__container
    img(src='@/assets/images/logo.png').header__container__logo
    .header__container__title Gellio
  .header__menu
    .header__menu__elem About
    .header__menu__elem Services
    .header__menu__elem Work
    .header__menu__elem Team
    .header__menu__elem Contacts 
  .fas.fa-bars
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
.header
  display flex;
  justify-content space-between
  align-content center
  margin-top 3em
  &__container
    display flex
    align-content center
    justify-content center
    padding-left 3em
    &__logo
      width 2em
      height 2em
      margin 0.3em
      padding-right 0.5em
    &__title
      font-family SFMedium
      font-size 2.125em
      letter-spacing -0.03em
  /*Menu element*/
  &__menu
    display flex
    margin-right 2em
    align-items center
    &__elem
      margin-right 2em
      padding-right 0.5em
      font-size 1.3em
      font-family SFMedium
	.fa-bars
		display none
//mobile view
.header
	@media(max-width 768px)
		margin 0em
		padding-top 0.5em
	&__container
		@media(max-width 768px)
			padding-left 0.5em
.header__menu
	@media(max-width 768px)
		display none
.fa-bars
	@media(max-width 768px)
		display flex
		font-size 1.5em
		justify-content center
		align-items center
		padding-right 1em
		cursor pointer
</style>
