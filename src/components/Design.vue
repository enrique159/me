<template>
  <div>
    <v-row class="contenedor pt-6">
      <v-col>
        <h4 class="titulo">_design</h4>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Diseño</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">Logotipo, Identidad de marca, Merchandising, Papelería Corporativa, 
          Elementos gráficos, iconografía y patrones, packaging.</p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Programas</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">illustrator, Photoshop, After Effects, Premiere Pro, Adobe Xd </p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Habilidades</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">Branding Design (Creación de marca), Animación digital, Edición de video, 
          Community Management, Diseño de conceptos visuales, Estrategias de contenido, Diseño de contenido. </p>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'design'
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