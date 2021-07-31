<template>
  <div id="app">
    <div id="nav">
      <router-link></router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: 'Unilever_Shilling';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

@font-face {
    font-family: 'Unilever_Shilling';
    src: url('./assets/fonts/UnileverShilling/UnileverShilling.eot');
    src: url('./assets/fonts/UnileverShilling/UnileverShilling.eot?#iefix') format('embedded-opentype'),
        url('./assets/fonts/UnileverShilling/UnileverShilling.woff2') format('woff2'),
        url('./assets/fonts/UnileverShilling/UnileverShilling.woff') format('woff'),
        url('./assets/fonts/UnileverShilling/UnileverShilling.ttf') format('truetype'),
        url('./assets/fonts/UnileverShilling/UnileverShilling.svg#UnileverShilling') format('svg');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}
</style>
