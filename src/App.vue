<template>
  <div class="body">
    <Header></Header>
    <Navbar></Navbar>
    <Advertisement></Advertisement>
    <Catalog></Catalog>
    <PopularProducts></PopularProducts>
    <Advantages></Advantages>
    <Delivery></Delivery>
    <Information></Information>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Navbar from "./components/Navbar.vue";
import Advertisement from "./components/Advertisement.vue";
import Catalog from "./components/Catalog.vue";
import PopularProducts from "./components/PopularProducts.vue";
import Advantages from "./components/Advantages.vue";
import Delivery from "./components/Delivery.vue";
import Information from "./components/Information.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Navbar,
    Advertisement,
    Catalog,
    PopularProducts,
    Advantages,
    Delivery,
    Information,
    Footer
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.body {
  max-width: 1024px;
  margin: auto;
}
</style>
