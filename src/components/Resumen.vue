<template>
  <div>
    <v-row class="contenedor paddingtop">
      <v-col>
        <h2 id="slogan">Para crecer tenemos que soltar cadenas, zarpar sin miedo a perder la costa.</h2>
        <p class="resumen">
          Soy un joven de 26 años originario de La Paz B.C.S, México, y me he dedicado los últimos años a
          crecer en las áreas de desarrollo para plataformas web y aplicaciones móviles, utilizando habilidades
          en diseño para crear UX/UI, conceptos y branding.
        </p>
        <p class="resumen">
          Desde hace 3 años aproximadamente me he dedicado en su mayoría al emprendimiento y freelance utilizando 
          mis conocimientos de programador tanto en desarrollo de aplicaciones móviles como desarrollo 
          web. Gracias al emprendimiento me he dado a la tarea de aprender un poco de todo, desde temas contables, 
          administración y liderazgo, hasta de marketing en social media, pero sobre todo diseño gráfico.
        </p>
        <p class="resumen">
          Me considero de una personalidad tipo ENTJ. Lo que más me apasiona es poder ser parte de algo que pueda
          cambiar la vida de las personas por medio de innovación digital.
        </p>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "resumen"
};
</script>

<style scoped>
.paddingtop {
  padding-top: 8em;
}

.resumen {
  font-size: 21px;
  line-height: 28px;
}

.contenedor {
  margin-left: 6%;
  margin-right: 6%;
}

#slogan {
  font-weight: bold;
  line-height: 48px;
  font-size: 48px;
  margin-bottom: 48px;
}

@media only screen and (min-width: 1080px) {
  .contenedor {
    margin-left: 16%;
    margin-right: 16%;
  }
}
</style>