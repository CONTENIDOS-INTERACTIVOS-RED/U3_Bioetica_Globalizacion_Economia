<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'El rol de las políticas globales en la protección de los derechos humanos y los recursos naturales'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p(data-aos="fade-left").mb-4 A nivel mundial, varias normas y políticas internacionales han sido implementadas para proteger tanto los derechos humanos como los recursos naturales:

    .row.align-items-center.mb-5
      .col-lg-7
        AcordionA(tipo="b")
          .div(titulo="Declaración Universal de los Derechos Humanos")
            p Un marco fundamental para la protección de los derechos humanos, es la Declaración Universal de los Derechos Humanos (DUDH), adoptada por la ONU en 1948. Aunque no aborda específicamente los recursos naturales, establece principios claves como el derecho a un nivel de vida adecuado, que incluye el acceso a recursos esenciales como agua, alimentos y un entorno saludable. Esta declaración subraya la relación entre el bienestar humano y la gestión responsable de los recursos naturales, de manera especial, para garantizar condiciones dignas de vida para todas las personas.

          .div(titulo="Agenda 2030")
            p La agenda 2030 para el desarrollo sostenible, también establece metas claras para gestionar los recursos naturales de manera responsable, garantizando que el acceso a estos recursos sea equitativo y sostenible (Naciones Unidas, 2015). Entre los Objetivos de desarrollo sostenible más relevantes, el ODS 6 se centra en garantizar el acceso a agua limpia y saneamiento, mientras que el ODS 13 promueve la acción climática para mitigar los impactos del cambio climático sobre las comunidades vulnerables. (Naciones Unidas, 2015)

          .div(titulo="Derechos comunicades indígenas")
            p Los derechos de las comunidades indígenas están protegidos a través de marcos normativos internacionales, como la Convención 169 de la OIT, que establece la necesidad de consultar a estas comunidades antes de la explotación de sus tierras o recursos naturales (Organización Internacional del Trabajo [OIT], 1989). Esto asegura que sus derechos territoriales sean respetados y que participen activamente en la toma de decisiones que afectan su entorno.

          .div(titulo="Protección de los recursos naturales")
            p Por otro lado, la protección de los recursos naturales está estrechamente vinculada a la justicia social. Las políticas internacionales abogan por un uso sostenible de los recursos para evitar la sobreexplotación y garantizar que los beneficios de estos sean distribuidos de manera justa, especialmente en las regiones más empobrecidas (Naciones Unidas, 2015). Las políticas también buscan prevenir la violación de derechos laborales en actividades extractivas y proteger a las poblaciones vulnerables que dependen directamente de los recursos naturales para su sustento. (Naciones Unidas, 2022)
      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/1.png", alt="").mt-4.mt-lg-0

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] Marco ético y legal de las políticas globales de sostenibilidad 

    p(data-aos="fade-left").mb-4 El marco legal de las políticas globales de sostenibilidad, está compuesto por una serie de acuerdos, convenciones y tratados internacionales que buscan regular el uso de los recursos naturales y garantizar que su explotación no contravenga los derechos humanos ni cause daño irreversible al medio ambiente.

    h3(data-aos="fade-left") Evolución de las políticas globales de sostenibilidad

    p(data-aos="fade-left").mb-4 Las políticas globales de sostenibilidad han evolucionado a lo largo de las últimas décadas, impulsadas por la creciente conciencia sobre los impactos ambientales, sociales y económicos del desarrollo. Inicialmente, el concepto de sostenibilidad se entendía principalmente desde una perspectiva ambiental, centrada en la conservación de los recursos naturales. Sin embargo, con el tiempo se ha adoptado un enfoque más integral que también considera la dimensión social y económica del desarrollo:


    .row.mb-5
      .col-12.col-md-10
        LineaTiempoE.color-primario
          .row(titulo="Década de 1970" subtitulo="")
            .col-md-8.col-xl-7.mb-4.mb-lg-0
              p En la década de 1970, el mundo comenzó a tomar conciencia de los problemas ambientales a través de eventos claves como la Cumbre de Estocolmo de 1972, que fue el primer encuentro mundial para discutir temas de desarrollo y medio ambiente. Este evento dio lugar a la creación del Programa de las Naciones Unidas para el Medio Ambiente, el cual ha sido fundamental en la evolución de las políticas ambientales globales.
            .col-md-4.col-xl-5
              figure
                img(src='@/assets/curso/tema2/2.png', alt='')
          .row(titulo="1987" subtitulo="")
            .col-md-8.col-xl-7.mb-4.mb-lg-0
              p Con el tiempo, la sostenibilidad se expandió para incluir la conservación de los recursos naturales, y el desarrollo humano. Un hito en esta evolución fue la publicación del informe de la Comisión Brundtland en 1987, titulado "Nuestro Futuro Común", que definió el concepto de desarrollo sostenible como aquel que "satisface las necesidades del presente sin comprometer la capacidad de las generaciones futuras, para satisfacer sus propias necesidades". Esta definición integró las dimensiones económica, social y ambiental del desarrollo.
            .col-md-4.col-xl-5
              figure
                img(src='@/assets/curso/tema2/3.png', alt='')
          .row(titulo="1992" subtitulo="")
            .col-md-8.col-xl-7.mb-4.mb-lg-0
              p Más tarde, en 1992, la Cumbre de la Tierra de Río (Cumbre de Río de Janeiro), marcó otro hito importante, puesto que consolidó el concepto de sostenibilidad en el ámbito global a través de la Agenda 21 y la Convención sobre la Diversidad Biológica. Estos acuerdos internacionales establecieron principios claves sobre la gestión de los recursos naturales y el respeto de los derechos humanos, en el contexto de la sostenibilidad.
            .col-md-4.col-xl-5
              figure
                img(src='@/assets/curso/tema2/4.png', alt='')


    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] Legislación internacional y local, sobre derechos humanos y recursos naturales


    p(data-aos="fade-left").mb-4 El enfoque global sobre la protección de los derechos humanos y los recursos naturales, está determinado por varios instrumentos y normativas internacionales que abordan, tanto los derechos de las personas como la sostenibilidad ambiental:

    .row.align-items-center.mb-5
      .col-lg-7
        AcordionA(tipo="b")
          .div(titulo="Declaración Universal de los Derechos Humanos (1948)")
            p Adoptada por la Asamblea General de la ONU, establece que todos los seres humanos tienen derecho a la vida, la libertad y la seguridad, así como a un nivel de vida adecuado, lo cual incluye el acceso a un medio ambiente saludable, aspecto que tiene una relación directa con la protección de los recursos naturales.

          .div(titulo="Protocolo de Kioto")
            p Acuerdo internacional que busca reducir las emisiones de gases de efecto invernadero (GEI) y así combatir el calentamiento global.


      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/5.png", alt="").mt-4.mt-lg-0


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
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
