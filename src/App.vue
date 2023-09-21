<script>

//Importo il componente "titolo"
import titolo from './components/AppTitle.vue'
//Importo il jumbo
import jumbo from './components/AppHero.vue'
//Importo la libreria di bootstrap
import 'bootstrap/dist/css/bootstrap.min.css'

export default{

  data(){

    return{
      message: 'Hello Vite',
      
    }
  },
  components:{
    titolo,
    jumbo
  }
}
</script>

<template>
  <titolo></titolo>
  <h2>{{ message }}</h2>
  <jumbo></jumbo>

</template>

<style>

</style>
