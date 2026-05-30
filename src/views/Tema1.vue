<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5.overflow-hidden
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Proyectos comunitarios agropecuarios

    .bloque-texto-t.justify-content-center.align-items-center.mb-0(data-aos="zoom-in-right")
      .bloque-texto-t__img.mb-0
        img(src='@/assets/curso/tema1/img_1.png')
      .bloque-texto-t__texto.col-10.mb-0
        p.mb-0 Un proyecto comunitario no solo implica la implementación de una actividad productiva, sino que integra procesos de organización social, fortalecimiento institucional, sostenibilidad ambiental y viabilidad financiera. Su esencia radica en la construcción participativa, donde la comunidad no es únicamente beneficiaria, sino protagonista en la toma de decisiones.

    Separador

    #t_1_1.titulo-segundo.color-acento-contenido
      .h2(data-aos="fade-right") 1.1	Concepto, tipos y alcance
    .mb-0 

    p.mb-3(data-aos="zoom-in-right") Un proyecto comunitario es un conjunto organizado de actividades planificadas, orientadas a resolver una necesidad colectiva previamente identificada en un territorio específico, mediante la participación de la comunidad beneficiaria. En el contexto rural, estos proyectos buscan mejorar las condiciones productivas, sociales, económicas y ambientales de las familias campesinas; fortaleciendo la autogestión y el desarrollo sostenible. Además de fortalecer la producción agropecuaria, los proyectos comunitarios promueven valores como la solidaridad, la cooperación, la participación social y el uso sostenible de los recursos naturales, contribuyendo al desarrollo rural sostenible y al bienestar colectivo. 

    .row.justify-content-center.align-items-center.mb-5
      .col-4.col-lg-1.mb-3.mb-lg-0(data-aos="zoom-in-right")
        figure
          img(src='@/assets/curso/tema1/img_2.svg', class="img-fluid")
      .col-12.col-lg-11
        p.mb-3(data-aos="zoom-in-right") Estos proyectos se construyen a partir de las necesidades, intereses y potencialidades del territorio, involucrando activamente a campesinos, asociaciones, organizaciones comunitarias e instituciones que trabajan de manera conjunta para alcanzar objetivos comunes.
        p.mb-0(data-aos="zoom-in-right") Un proyecto comunitario se caracteriza por:

    .row.justify-content-center.align-items-start.mb-4
      .col-6.col-lg-3.mb-3.mb-lg-0(data-aos="flip-left")
        figure
          img(src='@/assets/curso/tema1/img_3.png', class="img-fluid")
      .col-12.col-lg-9.mb-0(data-aos="zoom-in-right")
        AcordionA(tipo="a"  clase-tarjeta="tarjeta tarjeta--color-sistema-h")
          div(titulo="Responder a una problemática real del territorio")
            p.mb-0 Deben surgir de necesidades o dificultades reales que afecten a la comunidad rural, como problemas de producción, comercialización, acceso al agua o deterioro ambiental. 
          div(titulo="Contar con diagnóstico previo")
            p.mb-0 Antes de formular un proyecto, es necesario realizar un diagnóstico que permita conocer las problemáticas, recursos y necesidades del territorio. 
          div(titulo="Involucrar actores locales")
            p.mb-0 Los proyectos deben contar con la participación de campesinos, asociaciones, instituciones y demás actores del territorio, ya que su experiencia y compromiso fortalecen el desarrollo y sostenibilidad de las iniciativas comunitarias.
          div(titulo="Tener objetivos claros y medibles")
            p.mb-0 Los objetivos del proyecto deben indicar de forma precisa qué se quiere lograr, en cuánto tiempo y con qué resultados esperados, permitiendo organizar actividades y evaluar avances.
          div(titulo="Integrar sostenibilidad económica, social y ambiental")
            p.mb-0 Los proyectos comunitarios deben generar beneficios económicos, promover el bienestar social y proteger los recursos naturales para garantizar procesos productivos sostenibles en el tiempo.
          div(titulo="Promover el fortalecimiento organizativo")
            p.mb-0 Los proyectos deben contribuir al trabajo asociativo, el liderazgo comunitario y la participación rural, fortaleciendo la capacidad de la comunidad para gestionar iniciativas y mejorar sus condiciones de vida.

    .row.justify-content-center.align-items-start.mb-5
      .col-12.col-lg-10.mb-3.mb-lg-0(data-aos="flip-left")
        .cajon.color-secundario.p-4(data-aos="zoom-in-right")
          p.mb-0 Además, estos proyectos deben alinearse con los planes de desarrollo municipal, departamental y nacional, así como con políticas públicas relacionadas con el sector agropecuario y el desarrollo rural.

    .subtitulo-destacado.mb-5
      .subtitulo-destacado__icono
        img(src='@/assets/curso/tema1/img_3.png', aria-hidden='true').subtitulo-destacado__img
      .subtitulo-destacado__fondo
        h4.subtitulo-destacado__texto 


</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
