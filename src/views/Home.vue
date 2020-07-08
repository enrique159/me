<template>
  <div class="home">
    <Header></Header>
    <Resumen></Resumen>
    <Skills></Skills>
    <Development></Development>
    <Design></Design>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Resumen from "@/components/Resumen.vue";
import Footer from "@/components/Footer.vue";
import Skills from "@/components/Skills.vue";
import Development from "@/components/Development.vue";
import Design from '@/components/Design.vue'

export default {
  name: "Home",
  components: {
    Header,
    Resumen,
    Skills,
    Footer,
    Development,
    Design,
  }
};
</script>

<style>
</style>
