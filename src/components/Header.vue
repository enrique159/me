<template>
  <div>
    <v-row class="cabecera">
      <v-col cols="12" sm="12" md="8">
        <v-row justify="start" class="pl-3">
          <img id="logo" src="@/assets/logo.svg" alt="logotype" />
        </v-row>
        <h1 id="titulo">Hola! Soy Enrique Marín</h1>
        <h4 id="subtitulo">Software Developer & Graphic Designer</h4>
        <div class="pr-12 pt-4">
          <p class="texto">Me dedico a crear proyectos web como sitios para empresas, landing pages y
          tiendas e-commerce utilizando frameworks y estilos modernos, al igual que el 
          desarrollo de apps para Android y iOS. En los últimos años he tomado a la par
          la profesión de diseñador gráfico creando marcas,  diseño UI/UX, animación 
          y mucho más.. </p>
        </div> 
        <v-row>
          <v-btn class="boton" text small>Ver Resumen (PDF)</v-btn>
          <v-btn class="boton" text small href="#contacto" v-smooth-scroll="{ duration: 3000, offset: -50 }">Contactarme</v-btn>
        </v-row>
      </v-col>
      <v-col cols="12" sm="12" md="4">
        <img id="personalimg" src="@/assets/imagen-bn.jpg" alt="Imagen">
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "header"
};
</script>

<style scoped>
.cabecera {
  margin-left: 6%;
  margin-right: 6%;
  padding-top: 4em;
}

.boton{
  margin-right: 16px;
  margin-top: 24px;
  font-size: 20px !important;
  text-transform: none !important;
  letter-spacing: normal !important;
  font-weight: bold;
}

.texto{
  font-size: 18px;
}

#titulo{
  padding-top: 128px;
  font-weight: bold;
}

#subtitulo{
  font-weight: normal;
  font-size: 30px;
}

#logo {
  height: 24px;
}

#personalimg {
  height: 36em;
}

@media only screen and (min-width: 320px) {
  #titulo{
    padding-top: 60px;
    font-size: 48px;
  }
  #personalimg {
    height: auto;
    width: 100%;
  }
}

@media only screen and (min-width: 720px) {
  #titulo{
    padding-top: 128px;
  }
}

@media only screen and (min-width: 1080px) {
  .cabecera{
    margin-left: 16%;
    margin-right: 16%;
  }
  #personalimg {
    height: 36em;
    width: auto;
  }
}

</style>