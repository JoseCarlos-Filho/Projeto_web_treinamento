<template>
  <div class="page4">
    <div class="quadro_vermelho">
      <div class="bolinha"></div>
      <div class="quadro_branco">
        <p class="p1"><b>Planejar o tempo permite obter<br>mútiplas vantagens como:</b></p>
      </div>
    </div>

    <div class="conteiner">
        <div class="img_text">
          <img class="img2" src="~@/assets/screen_3/screen1.png" alt="">
          <p class="p2"><b>gerar uma visão<br> conjunta e global<br> das tarefas</b></p>
        </div>
        <div class="img_text">
          <img class="img2" src="~@/assets/screen_3/screen2.png" alt="">
          <p class="p2"><b>produzir automotivação<br> ao facilitar a <br>organização e aumentar <br>o compromisso com as<br> tarefas a realizar</b></p>
        </div>
        <div class="img_text">
          <img class="img2" src="~@/assets/screen_3/screen3.png" alt="">
          <p class="p2"><b>evitar distrações, ao<br> obter maior concentração</b></p>
        </div>
        <div class="img_text">
          <img class="img2" src="~@/assets/screen_3/screen4.png" alt="">
          <p class="p2"><b>fornecer informação<br> posterior a respeito do<br> próprio uso do tempo,<br> pelo que haverá maior <br>controle dos resultados</b></p>
        </div>
    </div>
    <hr>

    <p class="p3">Convidamos você a ingressar no primeiro módulo para conhecer quais são os fatores externos e internos, que incidem na gestão do tempo.<br>Vamos lá!</p>
  </div>
</template>

<script>
export default {
  name: 'Tela4',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
 @import '../scss/variables.scss';


  .page4 {
    position: relative;
    background-color: $cor-fundo-cinco;
    background-size: cover;
    height: 100vh;
    min-height: 668px;
  }

  .quadro_vermelho{
    display: flex;
    justify-content: center;
    height: 300px;
    max-width: 1366;
    background-color: $cor-fundo-seis;
  }

  .bolinha{
    height: 20px;
    width: 20px;
    margin-top: 100px;
    border-radius: 10px;
    background-color: $cor-fundo-dois;
  }

  .quadro_branco {
    position: absolute;
    height: 200px;
    width: 1200px;
    right: 85px;
    margin-top: 180px;
    background-color: $cor-fundo-cinco;
    border: $borda-um;
    box-shadow: 2px 2px 8px $cor-fundo-um;

  }

  .p1 {
    text-align: center;
    color: $cor-fundo-dois;
    font-size: 50px;
    margin-top: 40px;
    text-shadow: 1px 1px 2px $cor-fundo-texto-preto;
  }

  .conteiner{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 110px;
  }

  .img_text {
    display: inline-block;
    text-align: center;
  }

  .p2 {
    text-align: center;
    font-size: 20px;
    color: $cor-fundo-dois;
  }

  .img2 {
    height: 60px;
    width: 70px;
  }
  hr {
    margin-left: 200px;
    margin-right: 200px;
  }

  .p3 {
    text-align: center;
    font-size: 20px;
    color: $cor-texto-vermelho;
    text-shadow: 1px 1px 2px $cor-fundo-texto-preto;
  }
</style>
