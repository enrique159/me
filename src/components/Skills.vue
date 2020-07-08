<template>
  <div>
    <v-row class="contenedor paddingtop">
      <v-col cols="12" md="3">
        <h4 class="titulo">Idiomas</h4>
        <p class="texto">Español: Nativo<br>Inglés: 70%</p>
      </v-col>
      <v-col cols="12" md="5">
        <h4 class="titulo">Habilidades</h4>
        <p class="texto">Workteam, Project Management,<br>Liderazgo, Metodologías Agile</p>
      </v-col>
      <v-col cols="12" md="4">
        <h4 class="titulo">Hobbies</h4>
        <p class="texto">Videojuegos, Música, Viajes,<br>Cocinar, Aprender</p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col>
        <h4 class="titulo">Estudios</h4>
        <p class="texto">Ing. Sistemas Computacionales (2012-2018)<br>Tecnológico Nacional de México Campus La Paz</p>
      </v-col>
    </v-row>
    <v-row class="contenedor">
      <v-col cols="4" sm="2">
        <p class="texto">Worktools</p>
      </v-col>
      <v-col cols="8" sm="10">
        <p class="textogris">Trello, Asana, Swit, Slack, Microsoft Teams & Office (Top Powerpoint),
          Zoom, Google Meet, HubSpot CRM, Visual Studio Code, Athom.</p>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'skills'
}
</script>

<style scoped>

.paddingtop {
  padding-top: 2em;
}

.titulo{
  font-size: 28px;
  font-weight: bold;
}

.texto {
  font-size: 21px;
  line-height: 28px;
}

.textogris {
  font-size: 21px;
  line-height: 28px;
  color: #696969;
}

.contenedor {
  margin-left: 6%;
  margin-right: 6%;
}

@media only screen and (min-width: 1080px) {
  .contenedor {
    margin-left: 16%;
    margin-right: 16%;
  }
}

</style>