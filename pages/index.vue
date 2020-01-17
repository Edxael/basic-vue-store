<template>
  <div class="container">
    <div>
      <h1 class="title">E-Site</h1>
      <h2 class="subtitle">Best selection</h2>
      <div class="products-cont">
        <Products />
      </div>
    </div>
  </div>
</template>

<script>
// import Logo from "~/components/Logo.vue";
import Products from "~/components/ProductList.vue";

export default {
  components: {
    Products
  }
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  /* align-items: center; */
  margin-top: 30px;
  text-align: center;
}

.products-cont {
  margin-top: 30px;
}

/* .title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
} */

/* .subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
} */

/* .links {
  padding-top: 15px;
} */
</style>
