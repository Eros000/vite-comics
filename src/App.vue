<script>
import HeaderComponents from './components/HeaderComponents.vue'
import MainComponents from './components/MainComponents.Vue'
import FooterComponents from './components/FooterComponents.vue'

export default {
  data() {
    return {
      
    }
  },

  components: {
    HeaderComponents,
    MainComponents,
    FooterComponents
  },
}

</script>

<template>

  <HeaderComponents/>
  <MainComponents/>
  <FooterComponents/>
  
</template>

<style >

/* 
    RESET
*/
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* 
    GENERAL
*/
body {
    font-family: Arial, Helvetica, sans-serif;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

</style>
