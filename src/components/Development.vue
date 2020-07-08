<template>
  <div>
    <v-row class="contenedor pt-6">
      <v-col>
        <h4 class="titulo">_development</h4>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Lenguajes</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">Dart, JavaScript, C#, Java, php</p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Databases</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">MongoDB, MySQL, SQL Server, CloudFirestore</p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Tecnologías</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">Vue.js, Node.js, Express, Nuxt, Flutter, Flutter Desktop, DotNet, 
          HTML5&CSS3, Git, Github, BitBucket, Azure DevTools, Nginx, Apache, Wordpress, Firebase, 
          Terminal. </p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Habilidades</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">Diseño de User Experience, Prototipado Rápido, Wireframing, 
          Web Design, Front-End Development, Arquitectura y Diseño de Producto, Diseño Interactivo, 
          Diseño de User Interface. </p>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'development'
}
</script>

<style scoped>

.texto {
  font-size: 21px;
  line-height: 28px;
}

.titulo{
  font-size: 36px;
  font-weight: bold;
}

.contenedor {
  margin-left: 6%;
  margin-right: 6%;
}

.textogris {
  font-size: 21px;
  line-height: 28px;
  color: #696969;
}
  
@media only screen and (min-width: 1080px) {
  .contenedor {
    margin-left: 16%;
    margin-right: 16%;
  }
}

</style>