<template>
  <div class="our-vision-component-wrapper">
    <div class="our-vision-content">
      <div class="our-vision-image">
        <img src="@/assets/images/titulo-visao.png">
      </div>

      <div class="our-vision-text">
        <p>
          Acreditamos <br>
          que ninguém faz nada sozinho, <br>
          que ninguém se sente parte se não conversar, <br>
          que ninguém aprende sem testar, <br>
          que é preciso valorizar o passado e abraçar o novo. <br><br>

          Que criatividade e tecnologia juntas ampliam todo e qualquer potencial, <br>
          que os clientes e consumidores devem ser nossos pontos de partida e de <br>
          chegada, que nosso dia-a-dia deve ser diverso e sustentável. <br><br>

          Que com agilidade, ousadia e proximidade, <br>
          construímos um futuro brilhante 
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'OurVision',
}
</script>

<style lang="scss" scoped>
.our-vision-component-wrapper {
  background: url('../assets/images/bg/bg-2.jpg') top center no-repeat;
  height: 1490px;
  padding : 280px 20px 0;

  .our-vision-content {
    max-width: 1120px;
    margin: 0 auto;

    .our-vision-image {
      img {
        width: 100%;
        max-width: 332px;
      }
    }

    .our-vision-text {
      margin-top: 75px;
      p {
        font-size: 25px;
        line-height: 29px;
        color: #1304e5;
      }
    }
  }
}

@media(max-width: 768px) {
  .our-vision-component-wrapper {
    background: url('../assets/images/bg/bg-2-mobile.jpg') top center no-repeat;
    height: 1420px;

    .our-vision-content {
      .our-vision-text {
        p {
          font-size: 20px;
          line-height: 24px;
        }
      }
    }
  }
}
</style>