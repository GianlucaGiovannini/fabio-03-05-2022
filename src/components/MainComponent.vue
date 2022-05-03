<template>
  <main>
    <h1>Lista Prodotti</h1>
    <ProductList />
    
  </main>
</template>


<script>
import ProductList from '@/components/ProductList.vue'
export default {
  name: "MainComponent",
  components : {
      ProductList
  }
};
</script>


<style lang="scss" scoped>
main {
  background-image: url("@/assets/img/fondo-pag-speciali.jpg");
  background-size: cover;
  min-height: 50vh;
  padding-bottom: 2rem;
  h1 {
    text-align: center;
    padding: 2rem 0;
  }
}
</style>