<template>
  <section class="p-header">
    <h1 class="p-header__image">
      <img class="p-header__image--menu" src="~/assets/images/header/header_icon_hamburger.svg" alt="">
    </h1>
  </section>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
@import "~/assets/scss/common.scss";

.p-header {
  position: fixed;
  width:100%;
  // background-color: white; 
 background-color: rgba( 204, 255, 204, 0 ); 

  &__image {
    display: flex;
    &--menu {
      margin-left: auto;
      margin-right: 20px;
      width: 46px;
      height: 46px;
    }
  }
}
</style>
