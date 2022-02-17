<template>
  <div class="page8">
    <div class="box_amarelo">
      <div class="box_azul">
        <h2 class="t1">Frequentemente percebemos que o tempo de nossa jornada de trabalho
            não nos é suficiente para realizar tudo o que deveríamos.
        </h2>
        <h3 class="t2">Os diferentes fatores internos que atentam contra
            uma correta gestão do tempo são:
        </h3>
      </div>
    </div>
    <div class="box_branco">
      <div class="circulo">
        <h4>Falta de Planejamento</h4>
      </div>
      <div class="circulo">
        <h4>Perfeccionismo</h4>
      </div>
      <div class="circulo">
        <h4>Biorritmo de cada pessoa</h4>
      </div>
      <div class="circulo">
        <h4>Incapacidade para delegar tarefas</h4>
      </div>
      <div class="circulo">
        <h4>Atitude não assertiva</h4>
      </div>
    </div>
    <div class="rodape">
      <h3 class="t3">Conheça em detalhes cada um deles</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tela8',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../scss/variables.scss';

  .page8 {
    position: relative;
    background-color: $cor-fundo-cinco;
    background-size: cover;
    height: 100vh;
    min-width: 668px;
  }

  .box_amarelo {
    display: flex;
    justify-content: center;
    height: 300px;
    width: 100%;
    background-color: $cor-fundo-dois;
  }

  .box_azul {
    display: flex;
    flex-direction: column;
    height: 350px;
    width: 90%;
    margin: -25px;
    background-color: $cor-fundo-tres;
    border-radius: 20px;
    box-shadow: 0px 2px 8px 0px $cor-fundo-um;
  }

  .t1 {
    text-align: center;
    color: $cor-texto;
    margin: 120px 100px 40px 100px;
    font-size: 2.2rem;
  }

  .t2 {
    text-align: center;
    color: $cor-texto;
    margin: 0px 240px 40px 240px;
    font-size: 1.5rem;
  }

  .box_branco {
    display: flex;
    justify-content: space-around;

    height: 368px;
    width: 100%;
    background-color: $cor-fundo-cinco;
  }

  .circulo:nth-child(odd) {
    height: 150px;
    width: 150px;
    border-radius: 75px;
    background-color: $cor-fundo-quatro;
    margin-top: 100px;
    box-shadow: 0px 2px 8px 0px $cor-fundo-um;
    display: flex;
    align-items: center;
  }

  .circulo:nth-child(even) {
    height: 150px;
    width: 150px;
    border-radius: 75px;
    background-color: $cor-fundo-dois;
    margin-top: 100px;
    box-shadow: 0px 2px 8px 0px $cor-fundo-um;
    display: flex;
    align-items: center;
  }

  h4 {
    text-align: center;
    color: $cor-texto;
    margin: 0 auto;
  }

  .rodape {
    display: flex;
    justify-content: center;
  }

  .t3 {
    text-align: center;
    font-size: 2.0rem;
    color: $cor-fundo-tres;
    margin: -40px;
  }

  
</style>
