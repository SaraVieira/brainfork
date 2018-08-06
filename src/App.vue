<template>
  <div id="app">
    <Header />
    <Episodes/>
  </div>
</template>

<script>
import Episodes from './components/Episodes.vue'
import Header from './components/Header.vue'

export default {
  name: 'app',
  components: {
    Episodes,
    Header
  }
}
</script>

<style lang="scss">
body,
html {
  min-height: 100%;
  padding: 0%;
  margin: 0;
  background: #e2e253;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #07301e;
  margin-top: 60px;
}
ul {
  margin: 0;
  padding: 0;
}

a {
  color: #07301e;
  text-decoration: none;
}

.styles__segment___2WEVX {
  box-shadow: none;
}

.styles__anchorLogo___3V1bA .styles__anchorLogoDefault___137DJ {
  display: none;
}
</style>
