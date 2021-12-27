<template>
<section class="main">
  <Navbar/>
  <Hero/>
  <Dashboard/>
  <Companys/>
  <Features/>
  <AdsVeritical/>
  <Saflow/>
  <Pricing/>
  <AdsHorizontal/>
  <Footer/>

</section>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Dashboard from "./components/Dashboard.vue";
import Companys from "./components/Companys.vue";
import Features from './components/Features.vue';
import Saflow from "./components/Saflow.vue";
import AdsVeritical from "./components/AdsVeritical.vue";
import AdsHorizontal from "./components/AdsHorizontal.vue";
import Pricing from "./components/Pricing.vue"
import Footer from "./components/Footer.vue";

export default {
    name: "App",
    components: { Navbar, Hero, Dashboard, Companys, Features, Saflow, Pricing, AdsVeritical, AdsHorizontal, Footer }
}
</script>

<style>
body{
  height: hidden;
  background-color: var(--gray-900);
  font-family: var(--general-font);
  color: white;
}
</style>
