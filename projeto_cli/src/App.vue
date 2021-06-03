<template>
  <div id="app">
      <h1>Bem vindo ao meu primeiro projeto</h1>

      <Usuario/>

  </div>
</template>

<script>
import Usuario from './components/Usuario';
export default {
  name: 'App',
  components:{
    Usuario
  },
  data(){
    return{
      nome: "Ivan Santos de Jesus Júnior"
    }
  },
}
</script>

<style>

</style>