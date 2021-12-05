<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style scoped>
  #main-banner{
    background-image: url('/img/burger.jpg');

    /* desloca o banner no eixo y [praticamente subiremos ele um pouco] */
    /* background-position: 0 -250px; */
    /* comentei porque so estava a funcionar em tela cheia, ou seja, quando preenchida toda a resolucao da tela */

    /* para que a imagem apareca o maximo possivel na area que temos disponivel */
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;

    /* o conteudo estara alinhado a esquerda */
    justify-content: flex-start;

    /* background-repeat: no-repeat; */
  }
  #main-banner h1{
    color:#fff;
    text-align: center;
    font-size: 60px;
    background-color: rgba(34, 34, 34, 0.781);
    padding: 20px 40px;
  }
</style>