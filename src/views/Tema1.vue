<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Fundamentos de los riesgos en tránsito
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src="@/assets/curso/tema1/img01.png")
      .col-lg-8(data-aos="fade-left")
        p La conducción y el tránsito en general están definidas como una actividad que es peligrosa, pues cuando se decide tomar un volante y ser parte de uno de los actores viales, existe como en toda actividad una serie de riesgos que pueden llegar a producirse y desencadenar eventos como los accidentes de tránsito; por esta razón, si estos riesgos no son debidamente identificados y controlados a tiempo, no podrán ser mitigados adecuadamente con la finalidad de preservar la vida y la integridad de todos los peatones, los transeúntes, los pasajeros, los conductores de vehículos automotores y no automotores, los motociclistas, los ciclistas, los acompañantes, entre otros.
        p.mb-0 A continuación, se relacionan los diferentes tipos de riesgos más comunes en temas de tránsito y transporte y que en la mayoría de los casos generan los accidentes, las lesiones y muertes viales:

    .BGIMG01.p-4.mb-5(data-aos="zoom-in")
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Riesgos físicos
            p En los procesos de conducción, se presentan temas que afectan la salud debido a extensas jornadas al volante en una posición sedente, las vibraciones mecánicas que desembocan en fatiga, dolores en las extremidades, espalda, inflamaciones, riesgo postural, sobrepeso, inactividad física, sordera entre otros.
            p.mb-0 A nivel empresarial esto genera impactos económicos debido al ausentismo, discapacidad y limitaciones en las labores de sus conductores. Los riesgos físicos limitan de manera importante la capacidad de reacción frente a posibles accidentes en la vía.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema1/img02.png")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Riesgos químicos
            p Se dan por procesos propios del transporte, los equipos de transporte son abastecidos con combustibles fósiles, lo que ocasiona que los operadores estén en contacto permanente con elementos como plomo, bromo, aditivos de combustibles o con elementos químicos derivados de los productos transportados.
            p.mb-0 La emisión de estos combustibles es una de las fuentes principales de contaminación en el aire, generando partículas como óxidos de nitrógeno, responsables de impactos fuertes en los principales órganos de los seres vivos y en el calentamiento global. 
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema1/img03.png")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Riesgos biológicos
            p Debido a la infraestructura de transporte y los vehículos que prestan este servicio, se generan afectaciones por contaminantes biológicos, que son seres vivos, los cuales se multiplican y al estar dentro del organismo del ser humano causan enfermedades infecciosas o parasitarias.
            p.mb-0 No solo estos organismos son nocivos, también lo son las sustancias y secreciones que proceden de ellos y que varían a pesar de ser la misma especie, las variantes como la temperatura o la humedad del ambiente, permiten que se desarrollen en mejores condiciones.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema1/img04.png")
        .row.justify-content-center
          .col-lg-5.order-lg-1.order-2
            .h4 Riesgos ergonómicos
            p.mb-0 Están más asociados a los transportadores de carga que dentro de sus actividades diarias cargan y descargan productos, lo que deriva en daños a los huesos por caídas, torceduras y afectaciones a los órganos y músculos.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src="@/assets/curso/tema1/img05.png")

    .row.align-items-center.img02.mb-4(data-aos="fade-right")
      .col-lg-1.col-2.img01
        img.w-75(src="@/assets/curso/temas/img01.svg")
      .col-auto.BG02.p-2
        .h4.ms-5.mb-0.text-white Características de los tipos de riesgos

    p Por lo visto en los tipos de riesgos descritos anteriormente, también es importante conocer algunas de las características de cada uno de ellos; esto es:

    .cajon-b.color-acento-botones.mb-5(data-aos="flip-up")
      .row.align-items-center
        .col-lg-11
          p.mb-0 <span style="background-color:#FFF6E9; padding: 2px">#[b Características de los riesgos físicos]:</span> cómo afecta primordialmente la salud física dadas las horas tan extensas de conducción entre otras cosas, es importante generar hábitos y estilos de vida saludables, combatiendo sobre todo los comportamientos sedentarios y aumentar en aquellas actividades físicas que propenden por el mejoramiento de la salud cardiovascular y osteomuscular de las personas.
        .col-lg-1.col-2.p-3
          img(src="@/assets/curso/tema1/img06.svg")

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7.order-lg-1.order-2(data-aos="fade-right")
        p <span style="background-color:#FFF6E9; padding: 2px">#[b Características de los riesgos químicos]:</span> es importante además conocer los contaminantes del aire que se generan por procesos de combustibles fósiles, entre los que se encuentran:
        AcordionA.mb-5(tipo="a" clase-tarjeta="BGR03")
          div(titulo="Material particulado (MP)")
            p.mb-0 El humo negro que sale de los exostos de los vehículos o también conocido como hollín, posee altas concentraciones de material particulado, impactando especialmente los pulmones, generando problemas respiratorios y debilitando el sistema inmune.
          div(titulo="Compuestos orgánicos volátiles (COV)")
            p.mb-0 Estos compuestos son muy reactivos con los óxidos de nitrógeno y en presencia de la luz solar forman ozono, que queda en la superficie terrestre, lo que produce el llamado smog. El ozono en la atmósfera es protección a los rayos UV del sol, pero a niveles bajos es un gas que irrita las vías respiratorias y genera disminución pulmonar y asfixia.
          div(titulo="Óxidos de nitrógeno (NOx)")
            p.mb-0 Al igual que los compuestos orgánicos volátiles (COV) forman ozono a nivel del suelo y generan las mismas afecciones pulmonares.
          div(titulo="Monóxido de carbono (CO)")
            p.mb-0 Generado por la combustión de la gasolina de origen fósil, se presenta en forma de un gas y es tóxico, incoloro que bloquea la llegada de oxígeno al cerebro y a otros órganos vitales como el corazón.
          div(titulo="Dióxido de azufre (SO2)")
            p.mb-0 Este gas se genera por combustión del carbón y del diésel, formando partículas muy pequeñas que pueden ser inhaladas y altamente dañinas para niños y las personas asmáticas.
          div(titulo="Gases de efecto invernadero")
            p.mb-0 Son todos aquellos gases productos de la combustión de los vehículos y que atrapan calor en la atmósfera lo que trae como consecuencia calentamiento global.
      .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/tema1/img07.png")

    p Aunque existan riesgos químicos directos, existen otros secundarios y que en un largo plazo también generan dichos riesgos. 
    p <span style="background-color:#FFF6E9; padding: 2px">#[b Cacterísticas de los riesgos biológicos]:</span> las vías de entrada de los riesgos biológicos al organismo del ser humano, se presentan de la siguiente manera:

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-12.d-none.d-lg-flex
        img(src="@/assets/curso/tema1/img08.svg")
      .col-12.d-lg-none.d-flex
        img(src="@/assets/curso/tema1/img09.svg")
      
    p Los efectos que se derivan de este riesgo son enfermedades como las siguientes:

    .row.justify-content-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img10.svg' alt='AvatarTop')
          .tarjeta.color-primario.p-4
            p.text-center.mb-0 Infecciones.
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img11.svg' alt='AvatarTop')
          .tarjeta.color-primario.p-4
            p.text-center.mb-0 Envenenamiento o efectos tóxicos.
      .col-lg-4.col-8(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img12.svg' alt='AvatarTop')
          .tarjeta.color-primario.p-4
            p.text-center.mb-0 Alergias por la exposición a polvos orgánicos de mohos, enzimas o ácaros, que generan una reacción de los antígenos del organismo humano.

    p <span style="background-color:#FFF6E9; padding: 2px">#[b ❖	Características de los riesgos ergonómicos]:</span> se pueden derivar muchos otros riesgos de este tipo, aquí exponemos algunos muy frecuentes que afectan las actividades de locomoción, estos son:

    .row.justify-content-center.mb-4
      .col-lg-3.col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
        .BGR04.p-4
          .row.mb-4
            .col-lg-5.col-6
              img(src="@/assets/curso/tema1/img13.svg")
          .h4.mb-0 Caídas al mismo nivel y a distinto nivel.
      .col-lg-3.col-md-4.col-8.mb-md-0.mb-4(data-aos="flip-up")
        .BGR04.p-4
          .row.mb-4
            .col-lg-5.col-6
              img(src="@/assets/curso/tema1/img14.svg")
          .h4.mb-0 Atropellos por otros vehículos y/o equipos de trabajo en movimiento.
      .col-lg-3.col-md-4.col-8(data-aos="fade-left")
        .BGR04.p-4
          .row.mb-4
            .col-lg-5.col-6
              img(src="@/assets/curso/tema1/img15.svg")
          .h4.mb-0 Choques simples y accidentes de tránsito.

    .row.justify-content-center.mb-4
      .col-lg-3.col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
        .BGR04.p-4
          .row.mb-4
            .col-lg-5.col-6
              img(src="@/assets/curso/tema1/img16.svg")
          .h4.mb-0 Atrapamientos por vehículos o por otros equipos.
      .col-lg-3.col-md-4.col-8.mb-md-0.mb-4(data-aos="flip-up")
        .BGR04.p-4
          .row.mb-4
            .col-lg-5.col-6
              img(src="@/assets/curso/tema1/img17.svg")
          .h4.mb-0 Caída de objetos que están siendo manipulados, golpes, aplastamientos.
      .col-lg-3.col-md-4.col-8(data-aos="fade-left")
        .BGR04.p-4
          .row.mb-4
            .col-lg-5.col-6
              img(src="@/assets/curso/tema1/img18.svg")
          .h4.mb-0 Posturas forzadas al manipular cargas.

    p Existen otros factores de riesgo que cada día están tomando más relevancia y son los asociados a los #[b riesgos psicosociales] derivados del estrés y la fatiga mental. Las presiones laborales y el acoso generado por la falta de planeación en el trabajo y la poca adaptación a los métodos y procesos de las empresas y en sí de la vida cotidiana, generan que las vías y los vehículos se vuelvan elementos de desahogo generando fallas en la seguridad vial y riesgos para los otros actores de la vía.
    
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
