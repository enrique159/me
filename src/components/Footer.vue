<template>
  <div id="contacto">
    <v-row class="contenedor paddingtop">
      <v-col>
        <a href="https://bit.ly/enriquemarinh" target="_blank">Ver Resumen (482kb)</a> <br> <br>
        <a href="tel:6121049341">+52 612 104 9341</a> <br>
        <a href="mailto:enrique.marin.h@hotmail.com?subject=Contact%20From%20Page" target="_blank">enrique.marin.h@hotmail.com</a>
      </v-col>
    </v-row> 
    <v-row class="contenedor pt-6">
      <v-col>
        <a href="https://github.com/enrique159" target="_blank">Github</a>
        <br>
        <a href="https://www.behance.net/enriquemarin" target="_blank">Behance</a>
        <br>
        <a href="https://twitter.com/enriquemarin_mx" target="_blank">Twitter</a>
        <br>
        <a href="https://www.linkedin.com/in/enriquemarin/" target="_blank">LinkedIn</a>
      </v-col>
    </v-row> 
    <v-row class="pb-12"></v-row>
  </div>
</template>

<script>
export default {
  name: 'footer'
}
</script>

<style scoped>
.paddingtop{
  padding-top: 8em;
}

a, a:visited {
  font-weight: 600;
  font-size: 24px;
  color: black !important;
  text-decoration: none;
  position: relative;
}

a:after, a:visited:after {
  content: '';
  height: 3px;
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0%;
  background: rgb(0, 0, 0);
  transition: 0.2s;
}
a:hover:after, a:visited:hover:after {
  width: 100%;
}

.contenedor {
  margin-left: 6%;
  margin-right: 6%;
}

@media only screen and (min-width: 1080px) {
  .contenedor{
    margin-left: 16%;
    margin-right: 16%;
  }
}
</style>