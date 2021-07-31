<template>
  <div class="onepage-wrapper">
    <div class="home-wrapper">
      <div class="home-header-wrapper d-flex justify-content-center align-items-center">
        <img src="@/assets/images/logo-unilever.png">
      </div>

      <div class="home-body-wrapper">
        <div class="home-body-logo d-flex justify-content-center align-items-center">
          <img src="@/assets/images/logo-vem.png">
        </div>

        <div class="home-body-btn-list">
          <ul class="d-flex justify-content-center align-items-center flex-wrap">
            <li>
              <button
                @click="scrollMeTo('vision')"
                type="button"
                class="btn btn-outline-primary d-flex justify-content-center align-items-center"
              >visão
              </button>
            </li>

            <li>
               <button
                  @click="scrollMeTo('pillars')"
                  type="button"
                  class="btn btn-outline-primary d-flex justify-content-center align-items-center"
                >pilares
                </button>
            </li>

            <li>
              <button
                @click="scrollMeTo('ourWay')"
                type="button"
                class="btn btn-outline-primary d-flex justify-content-center align-items-center"
              >nosso jeito
              </button>
            </li>

            <li>
              <button
                @click="scrollMeTo('manifest')"
                type="button"
                class="btn btn-outline-primary d-flex justify-content-center align-items-center"
              >manifesto
              </button>
            </li>
          </ul>
        </div>
      </div>

      <div class="home-footer-wrapper">
       <div class="home-footer-content">
          <p>
            Queremos convidar você a conversar, participar e acompanhar esse novo momento da área de CD. Aqui, você vai saber tudo sobre nossos pilares estratégicos, nossas ações de transformação
            e principalmente acompanhar a evolução de
            cada uma delas.<br><br>

            Afinal, não basta falar, temos que fazer ;)
            Vamos?
          </p>
       </div>
      </div>
    </div>

    <div class="our-vision-wrapper" ref="vision">
      <OurVision />
    </div>

    <div class="pillars-wrapper" ref="pillars">
      <Pillars />
    </div>

    <div class="our-way-wrapper" ref="ourWay">
      <OurWay />
    </div>

    <div class="manifest-wrapper" ref="manifest">
      <Manifest />
    </div>

    <div class="footer-wrapper">
      <div class="footer-content">
        <div class="row">
          <div class="col-12 col-md-8">
            <p>Ninguém se sente parte se não conversar</p>

            <p>
              Então, se tiver dúvidas, se quiser dividir sua opinião e sugerir melhorias, vem conversar com a gente! Entre em contato
              por email conversadoria@unilever.com.br ou manda um Zap pro (11) XXXX-XXXX.
            </p>
          </div>

          <div class="col-12 col-md-4 d-flex justify-content-center align-items-center flex-column">
            <button
              type="button"
              class="btn btn-outline-primary d-flex justify-content-center align-items-center"
            >TERMOS E CONDIÇÕES
            </button>

            <button
              type="button"
              class="btn btn-outline-primary d-flex justify-content-center align-items-center"
            >FEEDBACK
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',

  components: {
    OurVision: () => import('@/components/OurVision.vue'),
    Pillars: () => import('@/components/Pillars.vue'),
    OurWay: () => import('@/components/OurWay.vue'),
    Manifest: () => import('@/components/Manifest.vue'),
  },

  methods: {
    scrollMeTo(refName) {
      const element = this.$refs[refName];
      const top = element.offsetTop;

      window.scrollTo({ top, behavior: 'smooth' });
    },
  }
}
</script>

<style lang="scss" scoped>
.onepage-wrapper {
  .home-wrapper {
    background: url('../assets/images/bg/bg-1.jpg') top center no-repeat;
    height: 1480px;
    padding: 30px 20px 0;

    .home-header-wrapper {
      img {
        width: 100%;
        max-width: 322px;
      }
    }

    .home-body-wrapper {
      padding-top: 190px;

      .home-body-logo {
        img {
          width: 100%;
          max-width: 750px;
        }
      }

      .home-body-btn-list {
        padding-top: 125px;

        ul {
          padding: 0;

          li {
            list-style: none;
            margin: 15px;

            .btn {
              &.btn-outline-primary {
                color: #ffffff;
                border-color: #ffffff;
                border-radius: 21px;
                border: 2px solid #ffffff;
                height: 41px;
                font-size: 35px;
                padding: 0 15px 8px;
                width: 225px;
              }
            }
          }
        }
      }
    }

    .home-footer-wrapper {
      max-width: 1100px;
      margin: 320px auto 0;
      direction: rtl;
      overflow: auto;
      height: 500px;
      padding: 100px 0 0 40px;

      &::-webkit-scrollbar {
        width: 25px;
        border-radius: 10px;
      }

      &::-webkit-scrollbar-track {
        background-color: transparent;
        border: 2px solid #1304e5;
        border-radius: 10px;
      }

      &::-webkit-scrollbar-thumb {
        background: #1304e5;
        border-radius: 10px;
      }
      
      .home-footer-content {
         direction: ltr;
        p {
          font-size: 25px;
          line-height: 29px;
          color: #1304e5;
          max-width: 640px;
        }
      }
    }
  }

  .footer-wrapper {
    background: #3212c5;
    max-width: 2000px;
    margin: 0 auto;

    .footer-content {
      max-width: 1020px;
      width: 90%;
      margin: 0 auto;
      border-top: 3px solid #ffffff;
      padding: 50px 20px;

      p {
        font-size: 18px;
        letter-spacing: 1px;
        line-height: 28px;
        color: #ffffff;
        max-width: 607px;
      }

      .btn {
        padding-bottom: 8px;
        &.btn-outline-primary {
          color: #ffffff;
          border-color: #ffffff;
          border-radius: 21px;
          border: 1px solid #ffffff;
          font-size: 19px;
          line-height: 23px;
          width: 240px;
          margin: 10px 0;
        }
      }
    }
  }
}

@media(max-width: 768px) {
  .onepage-wrapper {
    .home-wrapper {
      background: url('../assets/images/bg/bg-1-mobile.jpg') top center no-repeat;
      height: 1100px;

      .home-body-wrapper {
        .home-body-btn-list {
          ul {
            li {
              .btn {
                &.btn-outline-primary {
                  font-size: 25px;
                  height: 35px;
                  width: 200px;
                }
              }
            }
          }
        }
      }

      .home-footer-wrapper {
        max-width: 980px;
        margin: 220px auto 0;
        height: 332px;
        padding: 20px 0 0 40px;
      }
    }
    .footer-wrapper {
      .footer-content {
        p {
          font-size: 15px;
        }
      }
    }
  }
}

@media(max-width: 600px) {
  .onepage-wrapper {
    .home-wrapper {
      height: 1220px;
      .home-footer-wrapper {
        max-width: 980px;
        margin: 290px auto 0;
        height: 332px;
        padding: 20px 0 0 40px;
      }
    }
  }
}
</style>
