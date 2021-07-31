<template>
  <div class="pillars-component-wrapper">
    <div class="pillars-content">
      <img class="image-title" src="@/assets/images/titulo-pilares.png">

      <ul
        class="nav nav-tabs list-pilares d-flex justify-content-center justify-content-md-between flex-wrap"
        id="myTab"
        role="tablist"
      >
        <li class="nav-item" role="presentation">
          <div
            @click="scrollMeTo('people')"
            class="nav-link"
            id="people-tab"
            data-bs-toggle="tab"
            data-bs-target="#people"
            role="tab"
            aria-controls="people"
            aria-selected="false"
          >
            <img src="@/assets/images/botao-pessoas.png">
          </div>
        </li>
        <li class="nav-item" role="presentation">
          <div
            @click="scrollMeTo('customers')"
            class="nav-link"
            id="customers-tab"
            data-bs-toggle="tab"
            data-bs-target="#customers"
            role="tab"
            aria-controls="customers"
            aria-selected="false"
          >
            <img src="@/assets/images/botao-shoppers.png">
          </div>
        </li>
        <li class="nav-item" role="presentation">
          <div
            @click="scrollMeTo('resolve')"
            class="nav-link"
            id="resolve-tab"
            data-bs-toggle="tab"
            data-bs-target="#resolve"
            role="tab"
            aria-controls="resolve"
            aria-selected="false"
          >
            <img src="@/assets/images/botao-loucos.png">
          </div>
        </li>

        <li class="nav-item" role="presentation">
          <div
            @click="scrollMeTo('experience')"
            class="nav-link"
            id="experience-tab"
            data-bs-toggle="tab"
            data-bs-target="#experience"
            role="tab"
            aria-controls="experience"
            aria-selected="false"
          >
            <img src="@/assets/images/botaoo-eficiencia.png">
          </div>
        </li>
      </ul>

      <div class="tab-content" id="myTabContent">
        <div
          class="tab-pane fade"
          id="people"
          role="tabpanel"
          aria-labelledby="people-tab"
          ref="people"
        >
          <People />
        </div>

        <div
          class="tab-pane fade"
          id="customers"
          role="tabpanel"
          aria-labelledby="customers-tab"
          ref="customers"
        >
          <Customers />
        </div>
        
        <div
          class="tab-pane fade"
          id="resolve"
          role="tabpanel"
          aria-labelledby="resolve-tab"
          ref="resolve"
        >
          <Resolve />
        </div>

        <div
          class="tab-pane fade"
          id="experience"
          role="tabpanel"
          aria-labelledby="experience-tab"
          ref="experience"
        >
          <Efficiency />
        </div>
      </div>

      <ul class="list-icons d-flex justify-content-center justify-content-md-between flex-wrap">
        <li>
          <img src="@/assets/images/icone-tec.png">
        </li>

        <li>
          <img src="@/assets/images/icone-susten.png">
        </li>

        <li>
          <img src="@/assets/images/icone-diversidade.png">
        </li>

        <li>
          <img src="@/assets/images/icone-she.png">
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Pillars',

  components: {
    People: () => import('@/components/pillars/People.vue'),
    Customers: () => import('@/components/pillars/Customers.vue'),
    Resolve: () => import('@/components/pillars/Resolve.vue'),
    Efficiency: () => import('@/components/pillars/Efficiency.vue'),
  },

  methods: {
    scrollMeTo(refName) {
      const element = this.$refs[refName];
        if (element) {
        element.scrollIntoView({behavior: 'smooth'})
      }
    },
  },
}
</script>

<style lang="scss" scoped>
.pillars-component-wrapper {
  padding:  0 20px 120px;
  margin-top: -130px;
  .pillars-content {
    max-width: 1120px;
    margin: 0 auto;

    .image-title {
      margin: 0 0 65px;
      width: 100%;
      max-width: 385px;

    }

    .nav {
      margin-bottom: 30px;
      &.nav-tabs {
        border-bottom: none;
      }
      .nav-item {
        .nav-link {
          padding: 0;
          cursor: pointer;
        }

        &:hover {
          transform: scale(0.9);
        }
      }
    }

    .list-icons {
      margin-top: 75px;
      padding: 0;
      li {
        list-style: none;
        margin: 20px 0;
      }
    }
  }
}
</style>