<template>
  <div class="our-way-component-wrapper">
    <div class="our-way-content d-flex flex-column align-items-start">
      <img class="image title" src="@/assets/images/titulo-nosso.png">
      <img class="image desk" src="@/assets/images/img-nosso.png">
      <img class="image mobile" src="@/assets/images/img-nosso-mobile.png">
    </div>
  </div>
</template>

<script>
export default {
  name: 'OurWay',
}
</script>

<style lang="scss" scoped>
.our-way-component-wrapper {
  background: url('../assets/images/bg/bg-3.jpg') top center;
  height: 899px;
  padding : 100px 20px 0;
  max-width: 2000px;
  margin: 0 auto;

  .our-way-content {
    max-width: 1120px;
    margin: 0 auto;

    .image {
      width: 100%;
      max-width: 972px;

      &.title {
        max-width: 396px;
        margin-bottom: -40px;
      }

      &.mobile {
        display: none;
      }
    }
  }
}

@media(max-width: 768px) {
  .our-way-component-wrapper {
    background: url('../assets/images/bg/bg-3-mobile.jpg') top center;
    height: 100%;

    .our-way-content {
      max-width: 1120px;
      margin: 0 auto;

      .image {
        width: 100%;
        max-width: 972px;

        &.title {
        margin-bottom: 20px;
      }

        &.mobile {
          display: block;
          width: 100%;
        }

        &.desk {
          display: none;
        }
      }
    }
  }
}
</style>