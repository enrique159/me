<template>
  <div class="home">
    <Header></Header>
    <Resumen></Resumen>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Resumen from "@/components/Resumen.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Resumen,
    Footer
  }
};
</script>

<style>
</style>
