<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span 2
      h1 Enfermedad mental

    .tarjeta.fondo4.p-4.p-md-5.mb-5(data-aos="zoom-in")
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0(data-aos="zoom-in")
          img(src="@/assets/curso/tema1/figura1.png")

        .col-md.col-lg-6(data-aos="fade-up")
          .titulo-segundo.color-acento-contenido.mb-5
            h3.text-white.text-bold Enfermedad mental
          p.mb-4.text-white La existencia de personas con enfermedad mental al interior de los establecimientos de reclusión es una realidad presente en todos los países. En ocasiones por falta de la activación de un servicio de salud eficiente e integral se limita la posibilidad de identificar síntomas y activar tratamientos en salud mental oportunos, conllevando a los individuos a cometer delitos por los cuales son ingresados al sistema penitenciario, al respecto la Ley 1709 ordena realizar exámenes de ingreso y egreso y el lugar de la medida de aseguramiento según el estado clínico, en la siguiente infografía se profundizará sobre estos dos lineamientos:
          
          a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Enfermedad_mental.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download

    .row.align-items-center.my-5(data-aos="fade-left")
      .col-lg-10.col-md-12.fondo2.py-2.col-xl-8.col-xxl-7
        h3.mb-0.text-center.text-white.text-bold Atención intramural de las personas privadas de la libertad en salud mental 
    .row.mb-2
      .col-lg-6.col-md-10(data-aos="fade-right")
        span Está a cargo del prestador de servicio de salud intramural y/o de Instituto Prestador de Salud (IPS) contratada, que deben garantizar el acceso con 
        span.color-texto.text-bold calidad, oportunidad y continuidad
        span ; en este sentido, deben contar con el equipo multidisciplinario idóneo en las áreas de 
        span.color-texto.text-bold psiquiatría, medicina general, enfermería, psicología, trabajo social y terapia ocupacional y la red de servicios intramural y extramural en el territorio nacional 
        span , incluyendo actividades, procedimientos, intervenciones, insumos médicos, medicamentos y demás tecnologías en salud, que se requieran para la atención integral e integrada en salud mental de conformidad con lo preceptuado en la normatividad vigente, teniendo en cuenta la infraestructura disponible y el número total de las personas privadas de la libertad por Establecimiento de Reclusión del Orden Nacional (ERON).
        .row.mt-3
          .col-lg-2.col-md-2.col-sm-2.col-3
            img.mb-3.celular(src="@/assets/curso/tema2/lineas.svg")
          .col-lg-10.col-md-12
            p La atención integral en salud mental está enfocada en la prevención, atención integral e integrada, inclusión social, prevención del consumo de sustancias psicoactivas, eliminación de estigmas y la discriminación del enfermo mental garantizando el derecho a la salud mental.
      .col-lg-6.col-md-10(data-aos="zoom-in-up")
        img(src="@/assets/curso/tema2/imagen2.png")
    span.mb-3 En concordancia con la normativa expuesta, las personas jurídicamente declaradas inimputables se encuentran a cargo del Ministerio de Salud y de Protección Social (MinSalud); en caso de personas condenadas que presentan enfermedad mental que ingresan por primera vez o se encuentran al interior de los ERON, son valorados por la especialidad de psiquiatría para determinar el tratamiento farmacológico y psicoterapéutico a seguir; 
    span.color-texto.text-bold servicios que se encuentran a cargo de los prestadores de servicios de salud de acuerdo con el Manual técnico administrativo para la prestación de servicio de salud de la siguiente manera:

    .row.justify-content-center.fondo6.my-5.p-5.correr-izq.correr-der
      .col-12
        .row
          .col-1
          .col-lg-7.col-md-10(data-aos="fade-up")
            .titulo-sexto.color-acento-contenido.ms-5
              span.text-bold.text-small.text-dark Figura 1 
              span.text-dark.text-small Acciones promocionales de la salud mental
        .row.justify-content-center
          .col-lg-9.col-md-12(data-aos="fade-down")
            img(src="@/assets/curso/tema2/grafico1.svg")
    .row
      .col-lg-5.col-md-12(data-aos="zoom-in")
        img.mb-4(src="@/assets/curso/tema2/imagen3.png")
      .col-lg-7.col-md-12
        .row.align-items-center.mb-3
          .col-lg-8.col-md-7.col-8.col-xl-7.col-xxl-6.fondo2.py-2.ms-3(data-aos="fade-down-left")
            h3.mb-0.text-center.text-white.text-bold Valoración psicológica de ingreso
        span Está dirigida a evaluar el estado de salud psicológico actual y determinar la presencia de una patología mental, abuso o adicción a sustancias psicoactivas que requiera manejo por especialista de acuerdo con la prestación de servicio de salud mental establecido. Para todos los casos se debe realizar Tamizaje en Salud Mental a los pacientes con tuberculosis (TB) en riesgo, o en pérdida del seguimiento (idealmente a todos los pacientes; 
        span.color-texto.text-bold además del tamizaje al 100% de la población privada de la libertad de cada ERON, 
        span en índice de:
        ol.lista-ol--cuadro.my-3.ms-4(data-aos="fade-down-right")
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Consumo de sustancias psicoactivas (ASSIST).
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Patología mental.
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Suicidio.

    .row.align-items-center.my-4
      .col-lg-3.col-md-4.col-sm-5.col-6.fondo2.py-2.ms-3.col-xl-2(data-aos="fade-down")
        h3.mb-0.text-center.text-white.text-bold Consulta externa
    p.mb-5 La consulta externa es la atención que imparten los médicos a pacientes ambulatorios de las especialidades médicas que se ofrecen, consiste en realizar un interrogatorio y exploración física minuciosa para un diagnóstico.

    figure.mb-5
      .video(data-aos="fade-up")
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    span.my-5 Pese a que el 
    span.color-texto.text-bold Manual técnico administrativo indica las acciones y atenciones a realizar para la PPL de acuerdo con la normativa vigente
    span , a la fecha la prestación de servicios contratada por la fiduciaria central es la siguiente: 

    .tarjeta--container.row.my-5.mx-2
      .col-md.tarjeta.color-primario.p-5(data-aos="flip-right")
        .row.justify-content-center.mb-4
          .col-6
            h5.text-center CLÁUSULA PRIMERA
            p.text-center.text-bold Objeto
            figure
              img(src='@/assets/componentes/tema2/figura1.svg')
        p.text-center Prestación integral de servicios de salud de mediana-alta complejidad a la población privada de la libertad bajo la custodia y vigilancia del Instituto Nacional Penitenciario y Carcelario – Inpec, en la especialidad de salud mental en cumplimiento del modelo de atención en salud establecido en la Resolución 5159 de 2015, modificada por la Resolución 3595 de 2016 expedidas por el Ministerio de Salud y Protección social, garantizando los servicios intramurales en los ERON y extramurales en las instalaciones debidamente habilitadas.

      .col-md.tarjeta.fondo7.p-5(data-aos="flip-right")
        .row.justify-content-center.mb-4
          .col-6
            h5.text-center.text-white CLÁUSULA SEGUNDA
            p.text-center.text-white.text-bold Alcance
            figure
              img(src='@/assets/componentes/tema2/figura2.svg')
        p.text-white.text-center El contratista en desarrollo del objeto del presente contrato prestará integralmente los servicios de salud mental integral a la Población Privada de la Libertad (PPL) en los ERON que cuentan con unidades de salud mental, administración y entrega de medicamentos, así mismo garantizar los servicios extramurales de hospitalización y urgencias en las instalaciones debidamente habilitadas en cumplimiento del Decreto 780 de 2016. Lo anterior, de conformidad con el Anexo No.1 – Oferta de servicios del contratista, documento que para todos los efectos hace parte integral del contrato.

    .row.justify-content-center.fondo5.my-5.p-5.correr-izq.correr-der
      .col-12(data-aos="fade-down-left")
        p.text-center.bajar2 Conforme al alcance, se cuenta con los siguientes profesionales:
      .row.justify-content-center.alineacion(data-aos="fade-up-left")
        .col-xxl-3.col-lg-3.col-md-12.col-xl-3
          p.margen-texto.text-bold.mt-3 Atención Nacional Clínica Nuestra Señora de la Paz y Clínica Basilia: 

        .col-xxl-4.col-md-5.col-sm-6.col-lg.mb-5.mb-lg-0.bajar(data-aos="flip-right")
          .tarjeta-avatar.bajar.altura-tarjeta
            .tarjeta.fondo8
              img.reducir(src='@/assets/curso/tema2/figura1.svg')
              .p-4
                h3.text-center Médico psiquiatra
                p.margen-texto2.text-center Atención mensual a pacientes de control del programa y usuarios nuevos previa gestión de autorización y cumplimiento de ruta.
        .col-xxl-4.col-md-5.col-sm-6.col-lg.mb-5.mb-lg-0(data-aos="flip-right")
          .tarjeta-avatar.bajar.altura-tarjeta
            .tarjeta.fondo8
              img.reducir(src='@/assets/curso/tema2/figura2.svg')
              .p-4
                h3.text-center Auxiliar de enfermería
                p.margen-tarjeta.text-center En los ERON con más de treinta (30) pacientes en tratamiento.

    p.my-5 Unidad de Salud Mental de paso en establecimiento penitenciario, donde están los profesionales: 
    .row
      .col-lg-2
      .col-lg-6
        .titulo-sexto.color-acento-contenido.ms-5(data-aos="fade-down-left")
          span.text-bold.text-small.text-dark Figura 2 
          span.text-dark.text-small Equipo interdisciplinario
    .row.justify-content-center
      .col-lg-7.col-md-7.col-9.fondo8.py-2.ms-1(data-aos="fade-left")
        p.mb-0.text-center.text-bold Equipo interdisciplinario
    .row.justify-content-center
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.py-2.fondo12(data-aos="fade-down-left")
        img.reducir80(src='@/assets/curso/tema2/figura3.svg')
        p.text-center Médico psiquiatra
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.py-2(data-aos="fade-up-left")
        img.reducir80(src='@/assets/curso/tema2/figura4.svg')
        p.text-center Médico general
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.py-2.fondo12(data-aos="fade-left")
        img.reducir80(src='@/assets/curso/tema2/figura5.svg')
        p.text-center Psicólogo
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.py-2(data-aos="fade-right")
        img.reducir80(src='@/assets/curso/tema2/figura6.svg')
        p.text-center Enfermera jefa
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.fondo12.py-2(data-aos="fade-down-left")
        img.reducir80(src='@/assets/curso/tema2/figura7.svg')
        p.text-center Auxiliar de enfermería
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.py-2(data-aos="fade-down-right")
        img.reducir80(src='@/assets/curso/tema2/figura8.svg')
        p.text-center Trabajo Social
      .col-xl-1.col-lg-2.col-md-3.col-sm-3.col-9.py-2.fondo12(data-aos="fade-down")
        img.reducir80(src='@/assets/curso/tema2/figura9.svg')
        p.text-center Terapia Ocupacional

    .row.correr-der.correr-izq
      .col-12.fondo9
        .row.align-items-center.my-5.ms-5
          .col-lg-11.col-md-8.fondo2.py-2.col-xl-9.col-xxl-8.col-10(data-aos="fade-down-left")
            h4.mb-0.text-center.text-white.text-bold Rutas de acceso a la prestación de servicio de salud mental contratado por la Fiduciaria Central
        .row.justify-content-center
          .col-10.col-sm-7(data-aos="fade-left")
            p.text-center Para el acceso a psiquiatría de pacientes nuevos se debe seguir el siguiente proceso: 
        .row
          .col-lg-2
          .col-lg-7
            .titulo-sexto.color-acento-contenido.ms-4(data-aos="fade-down-right")
              span.text-bold.text-small.text-dark Figura 3 
              span.text-dark.text-small Acceso psiquiatría pacientes nuevos
        .row.justify-content-center
          .col-lg-8.col-md-10.col-sm-10.col-xs-9(data-aos="zoom-in")
            img.reducirgrafica(src='@/assets/curso/tema2/grafico2.svg')
        .row.my-5
          .col-11(data-aos="fade-down-left")
            p.text-center Para el acceso al control por la especialidad de psiquiatría:
        .row
          .col-lg-7.col-10.ms-4
            .titulo-sexto.color-acento-contenido.ms-5(data-aos="fade")
              span.text-bold.text-small.text-dark Figura 4 
              span.text-small.text-dark Acceso control por la especialidad de psiquiatría
        .row
          .col-11.ms-4.col-sm-10(data-aos="fade-down-left")
            img.my-5.ms-5.reducirgrafica(src='@/assets/curso/tema2/grafico3.svg')

        .row.my-5.justify-content-center 
          .col-10(data-aos="fade-down-right")
            p.text-center El acceso al control por la especialidad de la hospitalización psiquiatría:
        .row
          .col-lg-7.ms-4.col-sm-11.col-10
            .titulo-sexto.color-acento-contenido.ms-5(data-aos="fade-up")
              span.text-bold.text-small.text-dark Figura 5 
              span.text-small.text-dark Acceso control por la especialidad de la hospitalización psiquiatría
        .row
          .col-11.ms-4.col-sm-10(data-aos="zoom-in")
            img.my-5.ms-5.reducirgrafica(src='@/assets/curso/tema2/grafico4.svg')
    p.my-5 A continuación, en las tablas 1 y 2, se presentan los procesos de acceso a la Unidad de Salud Mental de Paso en establecimiento penitenciario y el de traslado de ERON a pacientes del Programa de Salud Mental.
    .row.my-4
      .col-lg-7
        .titulo-sexto.color-acento-contenido(data-aos="fade")
          h5 Tabla 1
          span.text-dark Unidad de Salud Mental de Paso en establecimiento penitenciario

    .tabla-a.color-acento-contenido.mb-5(data-aos="zoom-in-up")
      table
        thead
          tr
            th Actividad
            th Frecuencia
            th Responsable
            th Observaciones
        tbody.fondo12
          tr
            td Ingreso a Unidad de Salud Mental
            td De acuerdo con la necesidad indicada por el especialista.
            td Psiquiatra tratante intramural/ orden judicial.
            td Debe ser ordenada por médico psiquiatra tratante de la EPS e IPS prestadora del servicio de psiquiatría a nivel intramural, y/o por orden judicial debidamente soportada con peritaje de medicina legal.

    .row.my-4
      .col-lg-7
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2
          span.text-dark Traslado de ERON pacientes del Programa Salud Mental
    .tabla-a.color-acento-contenido.mb-5(data-aos="zoom-in-down")
      table
        thead
          tr
            th Actividad
            th Frecuencia
            th Responsable
            th Observaciones
        tbody.fondo12
          tr
            td.texto-arriba 
              p.mt-4 Permanencia en Unidad de Salud Mental (USM) por orden médica.
            td.texto-arriba 
              p.mt-4 De acuerdo con la necesidad indicada por psiquiatra de la USM.
            td.texto-arriba
              p.mt-4 Psiquiatra de la USM.
            td.texto-arriba 
              p.mt-4 1. El médico psiquiatra tratante intramural debe realizar la anotación en historia clínica de mejoría, estabilización clínica y necesidad de permanencia o no en unidad de salud mental. 
              p 2. Enfermería de la IPS o del consorcio, remite valoración y orden médica a la dirección del ERON para la solicitud de traslado a patio y/o pabellón o establecimiento de reclusión. 
              p En caso de que el especialista solicite el manejo del paciente fuera de la USM para otro pabellón en el mismo establecimiento de reclusión, la junta de patios del ERON determina el pabellón que cumpla con las características necesarias que garantice la adecuada convivencia y óptimas condiciones biopsicosociales para el interno, teniendo en cuenta el concepto del equipo de salud mental. 
              p * Si es traslado para otro establecimiento de reclusión, el director del establecimiento realizará solicitud de traslado, anexando los soportes a la Coordinación de Asuntos Penitenciarios Inpec. 
              p * Si se trata de una orden judicial; Jurídica del establecimiento de reclusión deberá, escribir al juez de conocimiento, anexando el concepto del médico psiquiatra, para que acepte y ordene el traslado a otro pabellón o establecimiento de reclusión.
</template>

<script>
import BannerInterno from '../components/BannerInterno.vue'
export default {
  name: 'Tema2',
  components: {
    BannerInterno,
  },
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
