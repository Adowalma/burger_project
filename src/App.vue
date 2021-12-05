<template>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <Footer/>
</template>

<script>
  import Navbar from "./components/Navbar.vue"
  import Footer from "./components/Footer.vue"
  export default {
    components:{
      Navbar,
      Footer
    },
    data(){
      return{
        logo_src:"/img/logo.png",
        app_name: "Make Your Burger"
      }
      
    }
  }
</script>

<style>
  /* especie de reset para limpar o css a mais que ja vem com o navegador [ * refere-se a todos os elementos] e padronizar a little the project */
  * {
    font-family: Helvetica;
    padding:0;
    margin:0;

    /* para que os inputs nao passem da largura maxima da div pai*/
    box-sizing: border-box;
  }

  .main-container{
    margin: 50px;
    
    /* altura minima */
    min-height: 250px;
  }
  h1{
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>
