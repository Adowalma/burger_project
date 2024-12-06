<template>
  <Banner/>
  <div class="main-container">
    <h1>Monte o burger</h1>
    
    <BurgerForm/>
  </div>
</template>

<script>
  import Banner from "../components/Banner.vue"
  import BurgerForm from "../components/BurgerForm.vue"

  export default {
    components: {
      Banner,
      BurgerForm
    } 
  }
</script>

<style>
.main-container{
    border-radius: 12px;
    box-shadow: 0 20px 40px #010824;
    padding:  5% 0px 5%;
  }
</style>
