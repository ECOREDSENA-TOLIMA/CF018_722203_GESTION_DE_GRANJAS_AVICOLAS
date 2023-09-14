<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-primario
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.mb-4(data-aos="fade-down")
      .col-12
        p La información que contiene los diferentes procedimientos establecidos para llevar a cabo la recolección de datos y su análisis, mediante la aplicación de los principios estadísticos y herramientas ofimáticas, de acuerdo con criterios técnicos, permite categorizar indicadores, así como generar planes de contingencia en aquellos procesos que se estén viendo afectados. En el siguiente vídeo podrá enterarse de manera general sobre los temas que se tratarán en el presente componente formativo:

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/avtmk4b1jpg" title="Sistematización y herramientas ofimáticas" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Sistematización y herramientas ofimáticas


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
