<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p Se debe tener el conocimiento de todos aquellos factores que puedan afectar al ser humano en procesos de conducción como la postura, el sueño, el estrés, la alimentación, la exposición a elementos de la carga y del medio ambiente, pues todo esto influye en los comportamientos. Si ocurren los accidentes, los intervinientes deben tener la capacidad de dar ayuda y proveer los primeros auxilios, manteniendo las condiciones de vida de los afectados y procurando evitar que las lesiones posteriores empeoren su condición, además de tener la capacidad de evaluar la escena de la emergencia, aislarla, comunicarse adecuadamente con los cuerpos de rescate y evaluar las condiciones reales de los heridos.
    p.mb-5 Sabiendo esto y lo abordando en este componente formativo, es preciso detallar de manera estructurada los procesos ya vistos, a través del siguiente esquema conceptual:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
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
