<template>
  <div class="page7">
    <div class="box_amarelo">
        <div class="elementos">
          <img class="img1" src="../assets/screen_7/clock.png" alt="">
          <h1>Fatores internos</h1>
        </div>
    </div>
    <hr>
    <div class="caixa_lampada">
      <img class="img2" src="../assets/screen_7/box_lamp.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tela7',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../scss/variables.scss';

  .page7 {
    position: relative;
    background-color: $cor-fundo-cinco;
    background-size: cover;
    height: 100vh;
    min-width: 668px;
  }

  .box_amarelo {
    margin: -20px;
    height: 400px;
    max-width: 100%;
    background-color: $cor-fundo-dois;
  }

  .elementos {
    display: flex;
    align-items: center;
    flex-direction: column;
  }

  hr {
    
    max-width: 70%;
    margin: 20px auto;
    border: 1px solid;
    border-color: $cor-fundo-quatro;
    background: $cor-fundo-quatro;
  }

  .img1 {
    margin: 90px 0px 0px 0px;
  }

  h1 {
    color: $cor_texto;
    font-size: 80px;
    text-align: center;
    margin: 0;
  }

  .caixa_lampada {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .img2 {
    position: absolute;
    height: 400px;
    width: 400px;
    top: 290px;
  }
  
</style>
