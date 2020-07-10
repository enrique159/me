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
          tiendas e-commerce, al igual que el desarrollo de apps para Android y iOS utilizando frameworks
          y estilos modernos. En los últimos años he tomado a la par la profesión de diseñador gráfico 
          creando marcas,  diseño UI/UX, animación y mucho más.. </p>
        </div> 
        <v-row class="pl-3">
          <a class="boton" href="https://bit.ly/enriquemarin" target="_blank">Ver Resumen (PDF)</a>
          <a class="boton" href="#contacto" v-smooth-scroll="{ duration: 3000, offset: -50 }">Contactarme</a>
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
  margin-right: 24px;
  margin-top: 24px;
  font-size: 20px !important;
  text-transform: none !important;
  letter-spacing: normal !important;
  font-weight: bold;
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