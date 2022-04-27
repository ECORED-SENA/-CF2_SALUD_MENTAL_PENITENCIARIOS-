<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido(data-aos="fade")
      .titulo-principal__numero
        span 1
      h1 Entornos penitenciarios
    .row.justify-content-center.my-5(data-aos="fade-down")
      .col-lg-6.col-md-12
        .row.justify-content-center
          .col-lg-2.col-1
            img.celular(data-aos="fade-up")(src="@/assets/curso/tema1/lineas.png")
          .col-lg-10.col-11
            p Los entornos penitenciarios son lugares destinados al confinamiento de personas que han sido puestas en prisión preventiva por una autoridad judicial, y que han sido privadas de su libertad tras ser condenadas por un delito.
        .row.align-items-center.mt-4
          .col-xl-4.col-lg-5.col-md-3.col-6.fondo2.py-2.mb-4.ms-3.col-sm-4.col-4
            h3.mb-0.text-center.text-white.text-bold Características
        .row.mb-4(data-aos="fade-left")
          .col-12
            span.mb-0.my-3 Como lo citan Lopera y Medina (2020), la situación de salud que hoy viven las personas privadas de la libertad (PPL) trasciende el fenómeno biomédico de salud-enfermedad. Un abordaje más integral permite entenderla como resultante de la interacción entre los determinantes del orden estructural, institucional y personal. 
            span.color-texto.text-bold La situación de salud de las PPL es un problema de salud pública susceptible de transformación prioritaria.  
      .col-lg-6.col-md-12(data-aos="zoom-in-up")
        img(src="@/assets/curso/tema1/imagen.png")
    span De otra parte, la oficina del 
    span.color-texto.text-bold Alto Comisionado de las Naciones Unidas para los Derechos Humanos en Colombia, en el informe presentado en el año 2001
    span , describió entre otras condiciones, los entornos penitenciarios en el país.
    .row.mt-4.correr-izq.correr-der
      .col-12.fondo14
        SlyderD.my-5.mx-2(data-aos="zoom-in-down")(:datos.color-texto="datosSlyder")

        .bloque-texto-c.p-4.mt-4.mx-2.fondo6(data-aos="fade-up-left")
          i.fas.fa-quote-right
          h3.mb-2 Desde una perspectiva de salud pública, la compleja situación de salud en los EPC representa un riesgo no solo para las PPL, sino también para sus familias y el cuerpo de vigilancia y custodia y para la salud pública.
          .row.justify-content-end
            .col-lg-4.col-md-6.me-2
              span.justify-content-end - (Lopera y Hernández, 2020, p. 3)

        .row.align-items-center.my-5.mx-2(data-aos="fade-up")
          .col-xl-4.col-lg-4.col-md-6.col-sm-7.col-7.fondo2.py-2
            h3.mb-0.text-white.text-bold.text-center Factores de riesgo asociado

        .tarjeta.fondo4.p-4.p-md-5.mx-2(data-aos="fade-right")
          .row.justify-content-around.align-items-center
            .col-8.col-sm-6.col-md-4.mb-4.mb-md-0
              img(src="@/assets/curso/tema1/figura1.png")

            .col-md.col-lg-6
              .titulo-segundo.color-acento-contenido.mb-5
                h3.text-white.text-bold Entornos Penitenciarios
              p.mb-4.text-white Como lo anota Laverde y Tuberquia (2019) se han encontrado factores de riesgo que influyen directamente en la calidad de vida de la persona privada de la libertad, en la siguiente infografía se presentan estos factores de riesgo que impactan a esta población:
              
              a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/entornos_penitenciarios.pdf')" target="_blank" type="application/pdf")
                span Descargar
                i.fas.fa-file-download

</template>

<script>
import BannerInterno from '../components/BannerInterno.vue'
export default {
  name: 'Tema1',
  components: {
    BannerInterno,
  },
  data: () => ({
    // variables de vue
    datosSlyder: [
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">Hacinamiento crítico, frecuentemente severo.</p>',
        imagen: require('@/assets/template/tema1/imagen1.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">Tratos o penas crueles, inhumanos o degradantes, producto de la violencia y las malas condiciones de detención.</p>',
        imagen: require('@/assets/template/tema1/imagen2.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">La falta de separación de personas privadas de libertad por categorías.</p>',
        imagen: require('@/assets/template/tema1/imagen3.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">Infraestructura y condiciones higiénicas y sanitarias marcadamente deficientes.</p>',
        imagen: require('@/assets/template/tema1/imagen4.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">Falta o insuficiencia de atención médica adecuada.</p>',
        imagen: require('@/assets/template/tema1/imagen5.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">Inseguridad jurídica de las personas privadas de libertad, incluyendo la falta de un recurso efectivo ante la ley.</p>',
        imagen: require('@/assets/template/tema1/imagen6.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold;">Falta de acceso por parte de la mayoría de las personas privadas de libertad a la educación, al trabajo y a la recreación.</p>',
        imagen: require('@/assets/template/tema1/imagen7.jpg'),
      },
      {
        texto:
          '<p style="color: #3BA3F8; font-weight: bold; margin-top: 0;">Falta de tratamiento penitenciario y atención especializada requerida por muchas personas privadas de libertad, incluyendo las pertenecientes a los grupos vulnerables.</p>',
        imagen: require('@/assets/template/tema1/imagen8.jpg'),
      },
    ],
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
