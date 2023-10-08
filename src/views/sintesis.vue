<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p La sistematización y herramientas ofimáticas facilitan utilizar la estadística, en diferentes procesos, principalmente al obtener o recopilar datos, y su posterior análisis y evaluación, con el fin de llegar a conclusiones valederas y proactivas en la formulación de planes estratégicos a nivel empresarial o con el fin de formular acciones de mejoramiento, cuando se observan falencias en los procedimientos establecidos.
    p.mb-5 Estos datos se convierten en un lenguaje general para ser entendido por los actores del proceso, además que son un punto común para enfrentar el panorama propio de las organizaciones. En el siguiente mapa conceptual, podrá conocer la ruta de temas vistos anteriormente:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="Síntesis del componente formativo sistematización y herramientas ofimáticas.")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
