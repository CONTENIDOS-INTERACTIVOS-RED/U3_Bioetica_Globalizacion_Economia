<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Bioética aplicada al desarrollo económico sostenible'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
      .col-lg-7
        p(data-aos="fade-left") El desarrollo económico sostenible busca satisfacer las necesidades del presente sin comprometer la capacidad de las futuras generaciones, para satisfacer las suyas; este objetivo plantea dilemas éticos importantes, que implica equilibrar el crecimiento económico con la responsabilidad de preservar el medio ambiente y respetar los derechos humanos. 

        .bg-color-1.p-4(data-aos="fade-left").mb-4
          p(data-aos="fade-left").mb-0 La bioética, con sus principios de justicia, autonomía, beneficencia y no maleficencia, vistos en la primera unidad, ofrece un marco ético para guiar las decisiones económicas hacia un desarrollo verdaderamente sostenible.


    #t_1_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.1] Definición del desarrollo económico sostenible     

    .row.mb-5
      .col-lg-7
        p(data-aos="fade-left") Se define como un proceso de crecimiento que, además de generar riqueza, considera el bienestar de las personas y el medio ambiente. Este enfoque promueve un equilibrio entre las dimensiones económica, social y ambiental, esencial para mejorar la calidad de vida sin comprometer los recursos de futuras generaciones. Fernández García (2013), señala que el desarrollo sostenible solo es posible si se logra un equilibrio entre los factores que influyen en la calidad de vida, como el crecimiento económico, la igualdad de oportunidades y el respeto al medio ambiente. Además, menciona que las empresas deben encontrar formas de integrar mejoras en términos de prevención y cuidado ambiental, que también impulsen la productividad y la calidad de sus operaciones. Este patrón de crecimiento, conocido como sostenible, busca conciliar la competitividad económica con la responsabilidad social y ecológica, respondiendo a la demanda creciente de consumidores que consideran el impacto ecológico y social en sus decisiones de compra, como al optar por productos de bajo consumo o vehículos híbridos. (Fernández García, 2013)
      .col-lg-5
        figure
          img(src="@/assets/curso/tema1/2.png", data-aos="zoom-in")


    h3(data-aos="fade-left") Dimensión económica

    p(data-aos="fade-left") Implica la creación de riqueza y empleo, de manera que no comprometa los recursos naturales a largo plazo. Se enfoca en prácticas de producción y consumo responsables, que aseguren la viabilidad económica en el tiempo.


    .row.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema1/3.png", data-aos="zoom-in")
      .col-lg-7
        p(data-aos="fade-left").mb-4 Fernández García (2013), explica que una economía sostenible debe crear valor, tanto para el accionista como para la sociedad en su conjunto. Esto involucra, por un lado, asegurar el adecuado uso del capital para los propietarios y atender las demandas de los clientes con precios competitivos y productos de calidad; y, por otro, contribuir al bienestar de la sociedad, mediante la creación de empleo, el pago de salarios justos y el fortalecimiento de la confianza en la economía de mercado. 

        p(data-aos="fade-left").mb-4 Un desarrollo económico sostenible, busca que las generaciones futuras cuenten con mayores niveles de riqueza, renta per cápita y calidad de vida, asegurando así un crecimiento que sea inclusivo y sostenible (Fernández García, 2013).


    h3(data-aos="fade-left") Dimensión social

    p(data-aos="fade-left").mb-4 Se centra en la igualdad de oportunidades, el desarrollo de la capacidad de las personas y la mejora de la calidad de vida. Se enfoca en la creación de condiciones que permitan a las personas alcanzar su máximo potencial, independientemente de su origen social, económico o geográfico.

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            //- Referencia con enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.revistasice.com/index.php/CICE/article/download/6031/6031" target="_blank" rel="noopener noreferrer") De Castro Emilio Cerdá, F. J. A. L. M. (s/f). Las energías renovables en el ámbito internacional. Revistasice.com. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://natura.org.co/que-es-agricultura-sostenible-y-como-se-relaciona-con-el-monitoreo-climatico/" target="_blank" rel="noopener noreferrer") Natura, F. (2024, junio 6). ¿Qué es agricultura sostenible y cómo se relaciona con el monitoreo climático? Fundación Natura Colombia. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.revistaecosistemas.net/index.php/ecosistemas/article/view/614" target="_blank" rel="noopener noreferrer") Artaraz, M. (2002). Teoría de las tres dimensiones de desarrollo sostenible: . Ecosistemas, 11(2). 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/62332?page=170" target="_blank" rel="noopener noreferrer") Fernández García, R. (2013). La dimensión económica del desarrollo sostenible: ( ed.). ECU.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/274611" target="_blank" rel="noopener noreferrer") De Castro Emilio Cerdá, F. J. A. L. M. (s/f). Las energías renovables en el ámbito internacional. Revistasice.com. 
            //- Referencia sin enlace 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              span Cerdos criollos colombianos y agricultura sostenible. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              span De Janeiro, R. (1992). La declaración del Río sobre el Medio Ambiente y el Desarrollo. Río de Janeiro República Federativa del Brasil., aprobada en Estocolmo el, 16.

            //- Referencia de youtube 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/hlpTZbikazw?si=XGBJEV3L-9pTa-Gc" target="_blank" rel="noopener noreferrer") Empresas innovadoras.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/Kh5lpqxTw5M?si=NN1qB14TbGN9TxiU" target="_blank" rel="noopener noreferrer") Google, Microsoft y tesla, el verdadero rey de la inteligencia artificial.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/QKLjwCMyv3M?si=uAWhO9tnyghljaJg" target="_blank" rel="noopener noreferrer") Innovación y sostenibilidad.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1
</style>
