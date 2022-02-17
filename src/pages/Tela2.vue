<template>
  <div class="page2">
    <div>
      <h1>Seja bem-vindo ao curso <br>'Gestão do Tempo'</h1>
    </div>
    <hr>
    <div class="conteiner">
      <p>Frequentemente temos a sensação de que o tempo não é suficiente para realizar todas as atividades e compromissos. No entanto, organizar nosso tempo para administrá-lo produtivamente é possível, só devemos aprender a planejá-lo e realizar uma gestão eficiente desse planejamento.<br><br> Os temas que trabalharemos ao longo do curso serão de grande ajuda na hora de organizar nosso tempo, especialmente naqueles casos em que seja necessário realizar múltiplas tarefas dentro de um horário determinado.
      </p>
      <div class="img_fundo">
            <img class="img1" src="~@/assets/screen_1/screen1.png">
      </div>
    </div>
    <h2>Ao finalizar o curso você conhecerá as ferramentas necessárias para otimizar seu tempo.</h2>
    <div class="bola">
      <div class="bolinha"></div>
    </div>
    <div class="rodape"></div>
  </div>
</template>

<script>
export default {
  name: 'Tela2',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../scss/variables.scss';


  .page2 {
    position: relative;
    background-color: $cor-fundo-dois;
    background-size: cover;
    height: 100vh;
    min-height: 668px;
  }

  h1, p {
    color: $cor-texto;
    text-shadow: 1px 1px 2px $cor-fundo-um;
  }

  h1 {
    margin: 0;
    font-size: 70px;
    font-weight: 800;
  }

  p {
    font-size: 25px;
    text-align: right;
    width: 44%;
    margin-left: 40px;
  }

  hr {
    width: 70%;
    background-color: $cor-fundo-tres;
    border: none;
    height: 2px;
  }

  .conteiner {
    display: flex;
    align-items: center;
  }

  .img_fundo{
    position:absolute;
    right: 0px;
    background-color: $cor-fundo-quatro;
    height: 46%;
    width: 50%;
    text-align: right;
  }

  .img1 {
    position: relative;
    margin-top: 3px;
    height: 98%;
    width: 99%;
  }

  h2 {
    margin-top: 20px;
    font-size: 30px;
    text-shadow: 1px 1px 1px $cor-fundo-texto;
  }

  .bola {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .bolinha {
    height: 20px;
    width: 20px;
    border-radius: 10px;
    background-color: $cor-fundo-quatro;
  }

  rodape {
    height: 30px;
    background-color: $cor-fundo-rodape;
    margin-top: 30px;
    border-top: 1px solid $cor-borda-top;
  }

</style>
