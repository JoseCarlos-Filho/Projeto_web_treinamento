<template>
  <div class="page3">
    <div class="bola">
      <div class="bolinha"></div>
    </div>
    <div class="quadro_azul">
    </div>
    <div class="quadro_branco">
        <p><b>No curso você também vai conhecer os fatores pessoais e externos que incidem na gestão do tempo.
           Apresentaremos algumas recomendações para conseguir uma organização eficaz do tempo e os princípios para aprender a administrá-lo
           eficientemente.
           Oferecemos ferramentas de planejamento do tempo, focadas nas tarefas e nos objetivos a atingir.
           Além disso, como recursos adicionais, ofereceremos dicas para gerenciar um projeto em equipe, e conselhos para pessoas que trabalham fora do escritório e precisam otimizar o tempo produtivamente.</b></p>
    </div>
    <img src="~@/assets/screen_2/screen1.png" alt="" class="relogio">
  </div>
</template>

<script>
export default {
  name: 'Tela3',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '../scss/variables.scss';


  .page3 {
    position: relative;
    background-image: url('~@/assets/screen_2/screen0.png');
    background-size: cover;
    height: 100vh;
    min-height: 668px;
    margin: 0;
  }

  .bola {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .bolinha{
    height: 20px;
    width: 20px;
    border-radius: 10px;
    margin-top: 60px;
    background-color: $cor-fundo-quatro;
  }

  .quadro_azul {
    position: absolute;
    margin: 0;
    bottom: 0;
    background-color: $cor-fundo-tres;
    height: 300px;
    width: 100%;
  }

  .quadro_branco {
    position: absolute;
    bottom: 200px;
    background-color: $cor-fundo-cinco;
    border: $borda-um;
    box-shadow: 1px 1px 8px $cor-fundo-um;
    margin-right: 120px;
    margin-left: 120px;

  }

  p{
    text-align: center;
    font-size: 30px;
    color: $cor-fundo-quatro;
    text-shadow: 1px 1px 2px $cor-fundo-texto-preto;
    margin: 20px;
  }

  .relogio {
    height: 220px;
    width: 200;
    position: absolute;
    bottom: 0px;
    right: 585px;
  }
</style>
