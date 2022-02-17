<template>
  <div class="page5">
    <div class="container">
      <div class="quadro-preto">
            <p class="p1"><b>Nada é mais valioso que o nosso<br> tempo por isso devemos aprender<br> a administrá-lo de maneira eficaz.</b></p>

            <p class="p2">A gestão do tempo consiste em planejar e distribuir o trabalho de modo que cada ação
            se realize no momento adequado.<br>
            É muito importante considerar que otimizar o tempo não significa aumentar as horas
            dedicadas a realizar uma tarefa é fazer um bom uso do tempo disponível.<br>
            Fique atento, pois existem muitas ações para administrar eficazmente o tempo!
            </p>
      </div>
    </div>
    <div class="bola">
      <div class="bolinha"></div>
    </div>
    <div class="rodape"></div>
  </div>
</template>

<script>
export default {
  name: 'Tela5',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
 @import '../scss/variables.scss';


  .page5 {
    position: relative;
    background-color: $cor-fundo-tres;
    background-size: cover;
    height: 100vh;
    min-height: 668px;
  }

  .container {
    display: flex;
    align-items: center;
  }

  .quadro-preto {
    position: absolute;
    left: 0px;
    top: 15%;
    background-color: $cor-fundo-um;
    box-shadow: 1px 1px 2px $cor-fundo-cinco;
    height: 70%;
    width: 90%;
  }

  .p1 {
    color: $cor-texto;
    font-size: 50px;
    text-align: right;
    margin-right: 30px;
  }

  .p2 {
    color: $cor-texto;
    font-size: 30px;
    text-align: center;
    width: 90%;
    margin: 0 auto;
  }

  .bola {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .bolinha {
    height: 20px;
    width: 20px;
    margin-top: 650px;
    border-radius: 10px;
    background-color: $cor-fundo-dois;
  }

  .rodape {
    border-top: 2px solid $cor-fundo-rodape;
    position: absolute;
    background-color: $cor-fundo-rodape;
    height: 10px;
    width: 100%;
    bottom: 0%;
  }

</style>
