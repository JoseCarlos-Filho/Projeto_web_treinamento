<template>
  <div class="page6">
    <div class="target">
      <img src="../assets/screen_5/screen6_target.png" alt="" class="img_target">
      <h1 class="titulo">O propósito deste modulo será:</h1>
    </div>
    <div class="container">
        <div class="filho1">
          <img src="../assets/screen_5/screen6_time-management.png" alt="" class="img_relogio">
        </div>
        <div class="filho2">
          <div class="text">
            <h2>#1</h2>
            <p>apresentar aqueles fatores internos e externos que incidem negativamente na gestão do tempo;</p>
          </div>
          <div class="text">
            <h2>#2</h2>
            <p>as causas que nos impedem de administrar nosso tempo produtivamente; e</p>
          </div>
          <div class="text">
            <h2>#3</h2>
            <p>nos dará mais ferramentas para evitá-las e superá-las.</p>
          </div>
        </div>      
    </div>
    <hr>
    <div class="rodape">
      <img src="../assets/screen_5/screen6_chevron.png" alt="" class="chevron">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tela6',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../scss/variables.scss';

  .page6 {
    position: relative;
    background-color: $cor-fundo-cinco;
    background-size: cover;
    height: 100vh;
    min-width: 668px;
  }

  .target {
    display: flex;
    justify-content: center;
    flex-direction: column;
    
  }

  .img_target {
     margin: 0 auto;
     padding-top: 60px;
  }

  .titulo {
    text-align: center;
    color: $cor-texto1;
    font-size: 40px;
    margin: 0;    
  }

  .container { 
     display: flex;
     align-items: center;
     height: 60%;
  }

  .filho1 { 
    margin-right: 15px;
    padding-left: 100px;
  }

  .img_relogio {
    width: 99%;
    height: 98%;
    position: relative;
    margin-top: 5px;
    box-shadow: #8302a7 0px 2px 8px 0px;
  }
  
  .filho2 { 
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    height: 90%;
    margin-left: 15px;
  }

  .text {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  h2 {
    font-size: 50px;
    text-shadow: 1px 1px 1px white;
    margin: 10px 0 0 0;
    color: $cor-texto1;
  }

  p {
    text-align: left;
    width: 80%;
    font-size: 25px;
    margin-left: 20px;
    color: $cor-texto2;
    font-weight: bold;
  }

  hr {
    width: 60%;
    border: 1px solid #8302a7;
    margin: 0 auto;
    margin-bottom: 34px;
    // border: 1px solid;
    // border-color: $cor-fundo-quatro;
    // background: $cor-fundo-quatro;
    // margin: 0px;
  }

  .rodape {
    display: flex;
    justify-content: center;
  }

  .chevron {
    position: absolute;
    z-index: 1;
    bottom: 0px;
  }

</style>