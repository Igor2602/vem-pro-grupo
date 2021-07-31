<template>
  <div class="manifest-component-wrapper">
    <div class="manifest-content">
      <div class="row">
        <div class="col-12 col-md-6">
          <h1>Manifesto</h1>
        </div>
      </div>
      <img src="@/assets/images/video.png">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Manifest',
}
</script>

<style lang="scss" scoped>
.manifest-component-wrapper {
  background: url('../assets/images/bg/bg-4.jpg') top center no-repeat;
  height: 1092px;
  padding : 255px 20px 0;

  .manifest-content {
    max-width: 1120px;
    margin: 0 auto;

    h1 {
      margin-bottom: 65px;
      font-size: 62px;
      line-height: 73px;
      color: #ffffff;
    }

    img {
      width: 100%;
    }
  }
}

@media(max-width: 768px) {
  .manifest-component-wrapper {
    background: url('../assets/images/bg/bg-4-mobile.jpg') top center no-repeat;
    height: 100%;
    padding : 255px 20px 50px;

    .manifest-content {
      h1 {
        font-size: 40px;
      }
    }
  }
}
</style>