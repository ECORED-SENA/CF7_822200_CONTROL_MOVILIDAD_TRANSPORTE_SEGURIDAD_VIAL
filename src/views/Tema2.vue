<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Técnicas de comunicación y códigos para comunicación de emergencias
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src="@/assets/curso/tema2/img01.png")
      .col-lg-8(data-aos="fade-left")
        p Dentro del desarrollo de los eventos de emergencias y accidentes de tránsito, las comunicaciones son una prioridad, puesto que es muy importante dar una información ajustada a la realidad, esto va a permitir que de la misma manera la respuesta sea dimensionada a la situación, en donde de acuerdo a la información que se comunique, se asignen los recursos adecuados y se disminuyan los tiempos de respuesta. Cada día el desarrollo tecnológico permite información cada vez más precisa y en tiempo real sobre tráfico o daños en las vías, pero esta se encuentra sujeta a la infraestructura, que en muchas ocasiones puede verse afectada por las mismas tragedias o accidentes, por lo que es importante conocer las alternativas existentes en las vías.
        p.mb-0 Las comunicaciones como base primaria de información en las emergencias, permiten coordinar a todos los grupos de salvamento; es por esto que a un nivel mucho más estructurado y dentro de la planificación de las comunicaciones en los cuerpos de salvamento, se analizan previamente los factores que se exponen a continuación, para dar respuesta a las posibles situaciones de emergencia:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        LineaTiempoD.color-acento-contenido
          p.mb-0(numero="1" titulo="Evaluación") Se debe evaluar la región o zona y su población, es decir hacer un análisis previo, determinando características sociales, tipos de población, zonas vulnerables, idiomas, posibles riesgos potenciales que puedan llegar a generar situaciones de emergencia y la definición de los mapas de riesgos.
          p.mb-0(numero="2" titulo="Respuesta") Capacidad de respuesta que se tiene frente a las emergencias, en cuanto a recursos disponibles, se determina en materia de comunicaciones los más utilizados en la zona afectada, con qué recursos humanos, técnicos y protocolos de comunicación para emergencias se tienen y evidencia de casos similares y lecciones aprendidas.
          p.mb-0(numero="3" titulo="Responsable") Asignación de una persona responsable de las comunicaciones, esto puede determinar la diferencia entre una emergencia atendida con éxito o atendida con fallas. En muchos casos los colapsos en las comunicaciones desencadenan problemas mayores, también se debe prever la posibilidad de una mala escucha o interpretación de los mensajes.
          p.mb-0(numero="4" titulo="Preparación") Se debe estar preparado para el manejo información continua, por lo que se debe tener en cuenta que puede haber gran variedad de grupos y personas, dando directrices de los medios de comunicación disponibles.
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/tema2/img02.png")

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src="@/assets/curso/tema2/img03.png")
      .col-lg-8(data-aos="fade-left")
        p De otra parte, se debe seleccionar los medios más apropiados de comunicación, de acuerdo a las características de la emergencia, pues a veces no siempre los dispositivos más sofisticados son los de mejor respuesta en situaciones como estas, por esto y en muchas situaciones de coberturas de señal o de las topografías de la zona, los equipos más simples funcionan mejor. 
        p.mb-0 En casos de catástrofes en donde es imposible utilizar estos medios convencionales, se puede utilizar comunicación vía satélite o los sistemas integrados de comunicaciones, pero esto requiere de personal capacitado. Adicionalmente, se deben tener en cuenta otras condiciones como:

    .BGIMG01.p-4.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Movilidad y transporte
            p.mb-0 Fácil movilidad y transporte, deben ser equipos portátiles, adaptables a diferentes lugares, con desplazamientos muy sencillos para cualquier carretera a pesar de que estén en mal estado. 
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema2/img04.png")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Intercomunicación
            p.mb-0 Posibilidad de intercomunicación, para comunicaciones con diferentes organismos locales y cuerpos diferentes de rescate participantes en la emergencia.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema2/img05.png")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Comunicaciones por telefonía fija y móvil
            p.mb-0 Si no hay interferencias se establecen comunicaciones por telefonía fija y móvil, si no es posible se hace por radio y si es un desastre de gran magnitud, se usan sistemas desplegables que conectan varios equipos portátiles integrados entre sí.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema2/img06.png")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Equipos independientes de infraestructuras
            p.mb-0 Si todos los equipos descritos anteriormente, no generan comunicaciones adecuadas por la magnitud de la emergencia, se recurre al uso de equipos independientes de infraestructuras, como los equipos vía satélite y los sistemas de radio HF-VHF.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema2/img07.png")

    p Es de resaltar que el lenguaje y las normas en este tipo de comunicaciones debe estar ajustado a unas pautas que deben conocer las personas que hagan uso de los medios de transmisión, optimizando las conversaciones, con menos duración, con mensajes claros que eviten errores de interpretación de los mensajes y no usar expresiones que generen confusión.

</template>

<script>
export default {
  name: 'Tema2',
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
