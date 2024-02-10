<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';
export default{ // se a prorpiedade é igual ao seu valor, pode deixa um nome só
  components: { Banner, ConteudoPrincipal}
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
</template>

