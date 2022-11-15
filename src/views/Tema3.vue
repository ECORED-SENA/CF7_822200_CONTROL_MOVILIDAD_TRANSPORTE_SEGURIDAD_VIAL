<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Técnicas de aseguramiento de la escena de emergencia
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        p Dentro de los protocolos de emergencia es fundamental la preservación y el cuidado inicial de la escena y los peligros que en lugar se puedan presentar al momento de brindar los primeros auxilios, por lo que es primordial realizar el debido aseguramiento de la escena teniendo en cuenta las medidas de precaución, delimitación y señalización del área donde se está atendiendo la contingencia, buscando con esto tener el control absoluto del lugar del acontecimiento y evitar así que se presenten efectos secundarios al personal que esté prestando sus servicio en atención a la emergencia, a las víctimas involucradas o a las personas que se encuentran cerca de la escena.
        p.mb-0 Previo a cualquier intervención en el área de emergencia, viene la valoración que debe tener en cuenta los siguientes puntos claves:
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/tema3/img01.png")
    
    .row.justify-content-center.mb-4
      .col-lg-3.col-md-6.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema3/img02.svg")
          .h4 Control del tráfico
          p.mb-0 Se debe realizar el respectivo control de tráfico antes de la intervención para minimizar los riesgos de exposición a un nuevo accidente.
      .col-lg-3.col-md-6.col-10.mb-lg-0.mb-4(data-aos="flip-up")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema3/img03.svg")
          .h4 Condiciones de vehículos
          p.mb-0 Se deben verificar las condiciones de los vehículos involucrados, corroborando la inestabilidad de los mismos o si existen riesgos de incendio por derrame de combustible.
      .col-lg-3.col-md-6.col-10.mb-lg-0.mb-4(data-aos="flip-up")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema3/img04.svg")
          .h4 Valorar la escena
          p.mb-0 Se debe valorar si en la escena está implicado materiales peligrosos como por ejemplo gases inflamables que puedan provocar una emergencia mayor.
      .col-lg-3.col-md-6.col-10.mb-lg-0.mb-4(data-aos="fade-left")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-4
            .col-6
              img(src="@/assets/curso/tema3/img05.svg")
          .h4 Evaluar estructuras
          p.mb-0 Se deben evaluar las estructuras eléctricas de alta tensión que puedan tener influencia en el área de emergencia.

    p Una vez se efectué la inspección y reconocimiento visual de la escena y antes de proceder a intervenir en el accidente, se transmitirá a la central de comunicaciones o emergencias la siguiente información:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        img(src="@/assets/curso/tema3/img06.png")
      .col-lg-7(data-aos="fade-left")
        ul.lista-ul--color
          li
            <i class="fas fa-check" style="color:#F88F05"></i>
            | Ubicación exacta del accidente.
          li
            <i class="fas fa-check" style="color:#F88F05"></i>
            | Número de víctimas o involucrados en la emergencia.
          li
            <i class="fas fa-check" style="color:#F88F05"></i>
            | Mecanismo lesional; es decir, evaluar si hay víctimas mortales, si fue colisión o choque frontal, choque lateral, embestida, si se presentó expulsión de los pasajeros fuera de los vehículos, si fue un accidente que involucra motociclistas o ciclistas, si se presentó atropello de peatón o precipitación de vehículos, entre otras otros.
          li
            <i class="fas fa-check" style="color:#F88F05"></i>
            | Riesgos secundarios por exposición en la escena.
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        p De acuerdo a lo planteado anteriormente, cuando se realice la identificación del mecanismo lesional presente en la escena, se deberá valorar los parámetros que intervienen en el mecanismo, como estado del vehículo y de acuerdo al mecanismo y evaluación de los factores analizados se plantea la sospecha de lesiones en los involucrados permitiendo encaminar los primeros auxilios hacia las necesidades del paciente.
        p.mb-0 La adecuada señalización del área de emergencia es fundamental para garantizar el alistamiento de la escena, evitando y controlando que los espectadores intervengan o generen demora en las acciones de primeros auxilios, así mismo evitar nuevos accidentes o mayores afectaciones en la escena existente, dando un mayor acceso al personal que atenderá la emergencia que de acuerdo al tipo de accidente deben valorar los siguientes parámetros:
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/tema3/img07.png")

    .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
      h5 Figura 1
      span Valoración de la escena de acuerdo al tipo de accidente.
      
    .BGIMG02.p-md-5.p-4
      figure(data-aos="zoom-in")
        img(src="@/assets/curso/tema3/img08.svg")

</template>

<script>
export default {
  name: 'Tema3',
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
