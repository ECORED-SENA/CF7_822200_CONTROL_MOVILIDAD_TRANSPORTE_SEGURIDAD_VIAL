<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center.align-items-center.BG01.p-4.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        p.mb-0 Estimado aprendiz, es momento de continuar con el proceso de aprendizaje, donde se desarrollarán temas que hablan de los riesgos físicos, químicos, biológicos y ergonómicos que pueden afectar el proceso de conducción; además de la necesidad de que el primer interviniente tenga la capacidad de evaluar la escena de la emergencia, aislarla, comunicarse adecuadamente con los cuerpos de rescate y evaluar las condiciones reales de los heridos para mantener estable la vida de los pacientes mientras son atendidos por organismos especializados en rescate. Sabiendo esto, le invitamos a revisar el siguiente video para identificar el contexto de aprendizaje  de este componente formativo:
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/intro/img01.png")

    figure(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
  
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
