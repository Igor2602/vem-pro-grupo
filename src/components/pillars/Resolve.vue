<template>
  <div class="people-component-wrapper">
    <div class="pillars-detail orange">
      <div class="row">
        <div class="col-12 col-sm-4">
          <div id="list-example" class="list-group mb-5">
            <a class="list-group-item list-group-item-action" href="#list-item-1">Loucos por resolver</a>
            <a class="list-group-item list-group-item-action" href="#list-item-2">Metas curto prazo</a>
            <a class="list-group-item list-group-item-action" href="#list-item-3">Metas médio prazo</a>
            <a class="list-group-item list-group-item-action" href="#list-item-4">Metas longo prazo</a>
            <a class="list-group-item list-group-item-action" href="#list-item-5">Impacto</a>
            <a class="list-group-item list-group-item-action" href="#list-item-6">KPIs</a>
            <a class="list-group-item list-group-item-action" href="#list-item-7">Responsáveis</a>
          </div>
        </div>

        <div class="col-12 col-sm-8">
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
                    Ouvir e reagir rápido para resolver problemas.
                    Testar e aprender quando estamos frente ao novo.
                    Tudo isso alimenta nosso espírito criativo e
                    protagonista.
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
                      Prototipar um modelo de escuta de stakeholders*
                      capaz de gerar insights e mapear oportunidades
                      priorizadas para resolução em modelo de teste ágil.
                    </span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-sm-4 pe-sm-0">
                  <div class="wrapper-content-secundary">
                    <p>Data início</p>
                    <span>01.07.21</span>
                  </div>
                </div>
                <div class="col-12 col-sm-4 px-sm-0">
                  <div class="wrapper-content-secundary">
                    <p>Data limite</p>
                    <span>01.01.22</span>
                  </div>
                </div>
                <div class="col-12 col-sm-4 ps-sm-0">
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

            <div class="wrapper-item secundary" id="list-item-3">
              <div class="row">
                <div class="col">
                  <div class="wrapper-header-secundary">
                    <p>Meta médio prazo</p>
                    <span>
                      Experimentar processos criativos com parcerias
                      especializadas em inovação (ecossistema) para
                      catalisar novas formas de solucionar problemas.
                    </span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-sm-4 pe-sm-0">
                  <div class="wrapper-content-secundary">
                    <p>Data início</p>
                    <span>01.07.21</span>
                  </div>
                </div>
                <div class="col-12 col-sm-4 px-sm-0">
                  <div class="wrapper-content-secundary">
                    <p>Data limite</p>
                    <span>01.07.22</span>
                  </div>
                </div>
                <div class="col-12 col-sm-4 ps-sm-0">
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
                      Criar uma célula de lab concisa capaz de
                      resolver problemas e transformá-los em
                      oportunidades escaláveis e replicáveis.
                    </span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-sm-4 pe-sm-0">
                  <div class="wrapper-content-secundary">
                    <p>Data início</p>
                    <span>01.07.21</span>
                  </div>
                </div>
                <div class="col-12 col-sm-4 px-sm-0">
                  <div class="wrapper-content-secundary">
                    <p>Data limite</p>
                    <span>01.07.23</span>
                  </div>
                </div>
                <div class="col-12 col-sm-4 ps-sm-0">
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
                  <span>Ser percebido como um agente transformador dos futuros do consumo.</span>
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
                <div class="col-12 col-sm-4 pe-sm-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Escutar 50% dos colaboradores /
                      Customers para mapear as dores
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">18%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-18.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-sm-4 px-sm-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Número de prototipos testados / implementados
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">67%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-67.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-sm-4 ps-sm-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Univoice: abertura ao erro / experimentação
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">43%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-43.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 col-sm-4 pe-sm-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Número de projetos testados e escalados
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">20%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-20.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-sm-4 px-sm-0">
                  <div class="wrapper-content">
                    <p class="primary-text">
                      Número de projetos de CD em Digifund e Leverup
                    </p>
                    <p class="progress-title">Progresso</p>
                    <p class="progress-porcent">71%</p>
                    <img class="image-progress" src="@/assets/images/progress-bar-72.png">
                    <span>Última atualização: 02.07.21</span>
                  </div>
                </div>

                <div class="col-12 col-sm-4 ps-sm-0">
                  <div class="wrapper-content">
                  </div>
                </div>
              </div>
            </div>

            <div class="wrapper-item fifth" id="list-item-7">
              <div class="row">
                <div class="col">
                  <p>Responsáveis</p>
                  <span>Rodrigo Visentini, Marcelo Costa, Lais Farhat, Paulo Chavarelli, Marcus Gasparotto</span>
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

    &.orange {
      .list-group {
      .list-group-item {
          color: #ffa91f;

          &.list-group-item-action {
            &:focus, &:hover, &.active {
              background-color: #ffa91f;
              color: #2435bf;
            }
          }
        }
      }
      .scrollspy {
        .wrapper-item {
          &.primary {
            p {
              color: #ffa91f;
            }
          }

          &.secundary {
            .wrapper-header-secundary {
              background-color: #ffa91f;

              p {
                color: #2435bf;
              }

              span {
                color: #2435bf;
              }
            }

            .wrapper-content-secundary {
              background-color: #fff9dd;
            }
          }

          &.third {
            background-color: #ffc000;

            p {
              color: #2435bf;
            }

            span {
              color: #2435bf;
            }
          }

          &.fourth {
            .wrapper-header {
              margin-top: 0px;
              margin-bottom: 1px;
              padding: 25px 25px 20px;
              background-color: #fcf4b6;
            }

            .wrapper-content {
              background-color: #fcf4b6;

            }
          }
        }
      }
    }
  }
}
</style>