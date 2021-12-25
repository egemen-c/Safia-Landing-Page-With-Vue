<template>
<section class="main">
  <Navbar/>
  <Hero/>
  <Dashboard/>
  <Companys/>
  <Features/>
</section>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Dashboard from "./components/Dashboard.vue";
import Companys from "./components/Companys.vue";
import Features from './components/Features.vue';

export default {
    name: "App",
    components: { Navbar, Hero, Dashboard, Companys, Features }
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
