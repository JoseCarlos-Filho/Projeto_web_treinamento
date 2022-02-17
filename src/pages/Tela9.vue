<template>
  <div class="page9">
    <div class="box_branco">
      <h1>Falta de Planejamento</h1>
    </div>
    <div class="box_azul">
      <h4>Esse é o primeiro fator que nos impede de administrar o nosso tempo.<br><br>
        Planejar é um processo complexo que ajuda a colocar ordem no trabalho e 
        permite conhecer a direção da atividade e as ações que devem ser
        utilizadas para realizá-la.<br><br>
        Só quando se tem presente um objetivo é que se pode ser estabelecida uma direção
        para atingi-lo.
      </h4>
      <img class="img1" src="@/assets/screen_9/tela9_img1.png" alt="">
    </div>
    <div class="bola">
          <div class="bolinha"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tela9',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../scss/variables.scss';

  .page9 {
    position: relative;
    background-color: $cor-fundo-cinco;
    background-size: cover;
    height: 100vh;
    min-width: 668px;
  }

  .box_branco {
    height: 200px;
    width: 100%;
    background-color: $cor-fundo-cinco;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  h1 {
    text-align: center;
    text-shadow: 0px 0px 5px $cor-fundo-um;
    color: $cor-texto2;
    font-size: 3.5rem;
    margin-top: 100px;
  }

  .box_azul {
    height: 468px;
    width: 100%;
    background-color: $cor-fundo-tres;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .img1 {
    height: 350px;
    width: 700px;
    margin: 0px 0px 40px 0px;
    box-shadow: -1px 0px 1px 2px $cor-fundo-dois;
  }

  h4 {
    text-align: right;
    color: $cor-texto;
    font-size: 1.5rem;
    margin: 0px 30px 40px 150px
  }

  .bola {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .bolinha {
    position: absolute;
    margin-bottom: 80px;
    height: 20px;
    width: 20px;
    border-radius: 10px;
    background-color: $cor-fundo-dois;
  }

</style>
