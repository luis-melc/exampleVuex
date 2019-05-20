<template>
  <div id="app" class="container">
    <Cabecera/>
    <Lista/>
  </div>
</template>

<script>
  import Cabecera from './components/cabecera/Cabecera'
  import Lista from './components/lista/Lista'

  export default {
    name: 'App',
    components: {
      Cabecera,
      Lista
    }
  }
</script>

<style>

</style>
