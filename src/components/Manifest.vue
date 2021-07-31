<template>
  <div class="manifest-component-wrapper">
    <div class="manifest-content">
      <div class="row">
        <div class="col-12 col-md-6">
          <h1>Manifesto</h1>
        </div>
      </div>
      <div class="wrapper-video d-flex justify-content-center align-items-center">
        <iframe src="https://www.youtube.com/embed/KxYJy1xYKcM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </div>
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
    height: 100%;
    max-height: 630px;

    h1 {
      margin-bottom: 65px;
      font-size: 62px;
      line-height: 73px;
      color: #ffffff;
    }

    .wrapper-video  {
      iframe {
        width: 1120px;
        height: 630px;
      }
    }
  }
}

@media(max-width: 1200px) {
  .manifest-component-wrapper {
    .manifest-content {
      .wrapper-video {
        iframe {
          width: 760px;
          height: 460px;
        }
      }
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

      .wrapper-video {
        iframe {
          width: 760px;
          height: 300px;
        }
      }
    }
  }
}

@media(max-width: 576px) {
  .manifest-component-wrapper {
    .manifest-content {
      .wrapper-video {
        iframe {
          width: 760px;
          height: 200px;
        }
      }
    }
  }
}
</style>