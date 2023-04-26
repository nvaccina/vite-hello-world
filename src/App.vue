<script>

import AppTitle from "./components/AppTitle.vue"
import AppHero from "./components/AppHero.vue"

export default {
  name:'App',
  components:{
    AppTitle,
    AppHero
  },

  data(){
    return{

    }
  }

}
</script>

<template>

  <AppTitle/>

  <AppHero/>


  

</template>

<style scoped>

</style>