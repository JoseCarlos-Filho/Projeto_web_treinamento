<template>
  <div class="page1">
    <div>
      <div class="container">

        <div class="titulo">
          <h1>Gestão do Tempo</h1>
          <h2>Módulo 1</h2>
        </div>

      </div>

      <div class="bottom"></div>
      <img src="~@/assets/screen_0/img2.png" alt="Avançar">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tela1',
  props: {
     msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../scss/variables.scss';

  .page1 {
    position: relative;
    background-image: url('~@/assets/screen_0/img1.png');
    background-size: cover;
    height: 100vh;
    min-height: 668px;
  }

  .titulo {
    position: absolute;
    right: 0;
    width: 900px;
    background-color: $cor-quadro-titulo;
    box-shadow: 1px 1px 2px $cor-fundo-um;
    text-align: right;
  }

  .container {
    display: flex;
    height: 100vh;
    align-items: center;
  }

  h1, h2 {
    margin: 0;
    text-shadow: 1px 1px 2px $cor-texto;
  }

  h1 {
    font-size: 90px;
  }

  h2 {
    font-size: 60px;
  }

  .bottom {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 10px;
    background-color: $cor-fundo-dois;
  }

  img{
    position: absolute;
    bottom: 0;
  }
</style>
