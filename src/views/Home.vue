<template>
  <div class="home">
    <Header/>
    <Hero/>
    <Product/>
    <Instagram/>
    <Logo/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '../components/Header.vue';
import Hero from '../components/Hero.vue';
import Product from '../components/Product.vue';
import Instagram from '../components/Instagram.vue';
import Logo from '../components/Logo.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'Home',
  components: {
      Header,
      Hero,
      Product,
      Instagram,
      Logo,
      Footer
  },
}
</script>
