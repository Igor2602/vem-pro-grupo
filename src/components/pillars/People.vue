<template>
  <div class="people-component-wrapper">
    <div class="pillars-detail">
      <div class="row">
        <div class="col-12 col-md-4">
          <div id="list-example" class="list-group mb-5">
            <a class="list-group-item list-group-item-action" href="#list-item-1">Pessoas e conexões potentes</a>
            <a class="list-group-item list-group-item-action" href="#list-item-2">Metas curto prazo</a>
            <a class="list-group-item list-group-item-action" href="#list-item-3">Metas médio prazo</a>
            <a class="list-group-item list-group-item-action" href="#list-item-4">Metas longo prazo</a>
            <a class="list-group-item list-group-item-action" href="#list-item-5">Impacto</a>
            <a class="list-group-item list-group-item-action" href="#list-item-6">KPIs</a>
            <a class="list-group-item list-group-item-action" href="#list-item-7">Responsáveis</a>
          </div>
        </div>

        <div class="col-12 col-md-8">
          <div
            data-bs-spy="scroll"
            data-bs-target="#list-example"
            data-bs-offset="0"
            class="scrollspy"
            tabindex="0"
          >
            <div class="wrapper-item primary" id="list-item-1">
              <div class="row">
                <div class="col">
                  <p>
                    Mais do que olhar para o que você faz,
                    queremos entender quem você é.
                    E assim investir no seu desenvolvimento,
                    fortalecer o sentimento de pertencimento
                    e potencializar suas habilidades e capacidades.
                  </p>
                </div>
              </div>
            </div>
            
            <div class="wrapper-item secundary" id="list-item-2">
              <div class="row">
                <div class="col">
                  <div class="wrapper-header-secundary">
                    <p>Meta curto prazo</p>
                    <span>
                      Desenvolver e compartilhar um modelo de
                      comunicação inclusiva, simples e frequente,
                      capaz de engajar com nossa visão, cultura,
                      valores e estratégia
                    </span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-md-4 pe-md-0">
                  <div class="wrapper-content-secundary">
                    <p>Data início</p>
                    <span>01.07.21</span>
                  </div>
                </div>
                <div class="col-12 col-md-4 px-md-0">
                  <div class="wrapper-content-secundary">
                    <p>Data limite</p>
                    <span>01.01.22</span>
                  </div>
                </div>
                <div class="col-12 col-md-4 ps-md-0">
                  <div class="wrapper-content-secundary">
                    <p class="mb-4">Meta alcançada?</p>
                    <div class="d-flex align-items-center">
                      <img class="me-2" src="@/assets/images/check-sim.png">
                      <p class="check-text mb-0">Sim</p>

                      <img class="mx-2" src="@/assets/images/check-nao.png">
                      <p class="check-text mb-0">Não</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="wrapper-item secundary" id="list-item-3">
              <div class="row">
                <div class="col">
                  <div class="wrapper-header-secundary">
                    <p>Meta médio prazo</p>
                    <span>
                      Fomentar as evoluções de lideranças mais horizontais,
                      ágeis e digitais através de uma agenda de educação
                      personalizada. 
                    </span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-md-4 pe-md-0">
                  <div class="wrapper-content-secundary">
                    <p>Data início</p>
                    <span>01.07.21</span>
                  </div>
                </div>
                <div class="col-12 col-md-4 px-md-0">
                  <div class="wrapper-content-secundary">
                    <p>Data limite</p>
                    <span>01.07.22</span>
                  </div>
                </div>
                <div class="col-12 col-md-4 ps-md-0">
                  <div class="wrapper-content-secundary">
                    <p class="mb-4">Meta alcançada?</p>
                    <div class="d-flex align-items-center">
                      <img class="mx-2" src="@/assets/images/check-nao.png">
                      <p class="check-text mb-0">Sim</p>

                      <img class="mx-2" src="@/assets/images/check-nao.png">
                      <p class="check-text mb-0">Não</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="wrapper-item secundary" id="list-item-4">
              <div class="row">
                <div class="col">
                  <div class="wrapper-header-secundary">
                    <p>Meta longo prazo</p>
                    <span>
                      Operar em um modelo de organização fluida,
                      ágil e horizontal e reconhecer genuinamente
                      as evoluções da cultura e resultados esperados.
                    </span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-md-4 pe-md-0">
                  <div class="wrapper-content-secundary">
                    <p>Data início</p>
                    <span>01.07.21</span>
                  </div>
                </div>
                <div class="col-12 col-md-4 px-md-0">
                  <div class="wrapper-content-secundary">
                    <p>Data limite</p>
                    <span>01.07.23</span>
                  </div>
                </div>
                <div class="col-12 col-md-4 ps-md-0">
                  <div class="wrapper-content-secundary">
                    <p class="mb-4">Meta alcançada?</p>
                    <div class="d-flex align-items-center">
                      <img class="mx-2" src="@/assets/images/check-nao.png">
                      <p class="check-text mb-0">Sim</p>

                      <img class="mx-2" src="@/assets/images/check-nao.png">
                      <p class="check-text mb-0">Não</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="wrapper-item third" id="list-item-5">
              <div class="row">
                <div class="col">
                  <p>Impacto</p>
                  <span>Time engajado com senso de pertencimento,
                    promovendo uma alta performance para si e para o negócio.
                  </span>
                </div>
              </div>
            </div>

            <div class="wrapper-item fourth" id="list-item-6">
              <div class="row">
                <div class="col">
                  <div class="wrapper-header">
                    <p>KPIs</p>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-md-4 pe-md-0">
                  <div class="wrapper-content">
                    <p class="primary-text">Métricas de Comunicação: clareza,
                      engajamento e frequência
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">45%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-45.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-md-4 px-md-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Métricas de Educação: 360ª das principais
                      interfaces sobre impacto de liderança e aplicação
                      de conceitos digitais
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">67%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-67.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-md-4 ps-md-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Univoice (Engagement, Inclusion, Performance, wellbeing)
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">21%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-21.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-md-4 pe-md-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Crescimento e Rentabilidade do Negócio (USG, UOM)
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">47%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-47.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-md-4 px-md-0">
                  <div class="wrapper-content">
                  </div>
                </div>

                <div class="col-12 col-md-4 ps-md-0">
                  <div class="wrapper-content">
                  </div>
                </div>
              </div>
            </div>

            <div class="wrapper-item fifth" id="list-item-7">
              <div class="row">
                <div class="col">
                  <p>Responsáveis</p>
                  <span>Fabiana Paredes, Ricardo Zuccollo, Carolina Mazziero, Nadiane Martins</span>
                </div>
              </div>
            </div>           
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.people-component-wrapper {
  .pillars-detail {
    .list-group {
      .list-group-item {
        border: none;
        border-bottom: 1px solid #f3f4fb;
        color: #2435bf;
        font-weight: 400;

        &.list-group-item-action {
          &:focus, &:hover {
            background-color: #2435bf;
            color: #fff;
            line-height: 14px;
          }

          &.active {
            background: transparent;
          }
        }
      }
    }
    .scrollspy {
      .wrapper-item {
        &.primary {
          p {
            color: #2435bf;
            font-size: 22px;
            line-height: 34px;
            margin-bottom: 40px;
          }
        }

        &.secundary {
          margin-bottom: 10px;
          .wrapper-header-secundary {
            margin-top: 20px;
            margin-bottom: 2px;
            padding: 25px;
            background-color: #2435bf;

            p {
              margin-top: 0px;
              margin-bottom: 15px;
              color: #fff;
              font-size: 20px;
              line-height: 20px;
            }

            span {
              font-size: 14px;
              line-height: 20px;
              color: #fff;
            }
          }

          .wrapper-content-secundary {
            padding: 20px 15px 35px 20px;
            border: 1px solid #fff;
            background-color: #ebedf9;
            height: 130px;

            p {
              color: #2435bf;
              font-size: 14px;
              line-height: 20px;
              font-weight: 600;
            }

            span {
              color: #2435bf;
              font-size: 30px;
              line-height: 30px;
              font-weight: 400;
            }

            .check-text {
              color: #2435bf;
              font-size: 18px;
              line-height: 18px;
              font-weight: 400;
            }
          }
        }

        &.third {
          background-color: #47c8ff;
          margin-top: 20px;
          margin-bottom: 2px;
          padding: 25px;

          p {
            font-size: 20px;
            line-height: 20px;
            margin-top: 0px;
            margin-bottom: 15px;
            color: #2435bf;
            font-weight: 600;
          }

          span {
            font-weight: 400;
            line-height: 1.5;
            font-size: 14px;
            color: #212529;
          }
        }

        &.fourth {
          .wrapper-header {
            margin-top: 0px;
            margin-bottom: 1px;
            padding: 25px 25px 20px;
            background-color: #c6f4ff;

            p {
              font-size: 20px;
              line-height: 20px;
              margin-top: 0px;
              margin-bottom: 15px;
              color: #2435bf;
              font-weight: 600;
            }
          }

          .wrapper-content {
            background-color: #c6f4ff;
            height: 330px;
            padding: 20px 15px 35px 20px;
            border: 1px solid #fff;

            .primary-text {
              margin-bottom: 30px;
              height: 130px;
              font-weight: 400;
              color: #2435bf;
              font-size: 14px;
              line-height: 20px;
            }

            .progress-title {
              color: #2435bf;
              font-size: 14px;
              line-height: 20px;
              font-weight: 700;
            }

            .progress-porcent {
              font-size: 50px;
              color: #2435bf;
              line-height: 30px;
              font-weight: 400;
              font-style: italic;
            }

            .image-progress {
              width: 100%;
            }

            span {
              font-size: 10px;
              color: #2435bf;
            }
          }
        }

        &.fifth {
          margin-bottom: 60px;
          background-color: #f3f3f3;
          margin-top: 20px;
          padding: 25px;

          p {
            font-size: 20px;
            line-height: 20px;
            margin-top: 0px;
            margin-bottom: 15px;
            color: #2435bf;
            font-weight: 600;
          }

          span {
            font-weight: 400;
            font-size: 14px;
            line-height: 1.5;
            color: #2435bf;
          }
        }
      }
    }
  }
}
</style>