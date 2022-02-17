<template>
  <div id="app">
    <logoheader></logoheader>
    <div class="main">
      <Tela1/>
      <Tela2/>
      <Tela3/>
      <Tela4/>
      <Tela5/>
      <Tela6/>
      <Tela7/>
      <Tela8/>
      <Tela9/>
    </div>
  </div>
</template>

<script>
import logoheader from './components/logoheader.vue'
import Tela1 from './pages/Tela1.vue'
import Tela2 from './pages/Tela2.vue'
import Tela3 from './pages/Tela3.vue'
import Tela4 from './pages/Tela4.vue'
import Tela5 from './pages/Tela5.vue'
import Tela6 from './pages/Tela6.vue'
import Tela7 from './pages/Tela7.vue'
import Tela8 from './pages/Tela8.vue'
import Tela9 from './pages/Tela9.vue'

export default {
  name: 'App',
  components: {
    logoheader,
    Tela1,
    Tela2,
    Tela3,
    Tela4,
    Tela5,
    Tela6,
    Tela7,
    Tela8,
    Tela9,
  }
}
</script>

<style lang="scss">
  body {
      margin: 0;
  }

  #app {
    overflow-x: hidden;
    overflow-y: hidden;
    font-family: Myriad Pro;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: black;
    margin-top: 0px;
  }

  .main {
    margin: 0 auto;
    max-width: 1366px;
    top: 0;
    position: relative;
  }
</style>
