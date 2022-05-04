<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Tecnología en Desarrollo Multimedia y Web
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Tecnología en Desarrollo Multimedia y Web
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 217320
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 3984 Horas
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto Virtual
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/nclUy3bqU40" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>            
           

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p El programa de formación “Tecnología en Desarrollo Multimedia y Web” se crea para dar respuesta a la necesidad constante en la que actualmente se encuentra inmerso el mundo. Precisamente se requiere contar con personas que tengan conocimientos de contenido multimedia para abordar todas las necesidades tecnológicas que encontramos en nuestro diario vivir.
    p En los últimos años el uso de diferentes tipos de medios y tecnologías de comunicación multimedia ha aumentado la visualización del contenido y la interacción del usuario con las herramientas utilizadas.
    p La evolución de las tecnologías ofrece nuevas oportunidades de integrar el mundo a través del uso del internet, pues el ser humano requiere de diferentes medios de comunicación para relacionarse con otros.
    p Buscando muchos beneficios, se puede encontrar que la multimedia, pretende generar una mayor comodidad frente a la experiencia comunicativa de sus usuarios, permitiendo acercamiento entre las personas que deseen establecer comunicación y que la distancia o las posibilidades de cercanía no lo permitan.
    p Por tales motivos, la Tecnología Desarrollo Multimedia y Web integra elementos de formación profesional, sociales, tecnológicos y culturales, aportando como elementos diferenciadores, metodologías y plataformas para el desarrollo de software de calidad, con acceso a tecnologías de última generación y una estructuración sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidaria y emprendedora, factores que lo acreditan y lo hacen pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias y cambios tecnológicos y las necesidades del sector empresarial y de los trabajadores, impactando positivamente la productividad, la competitividad, la equidad y el desarrollo del país.
    p El Tecnólogo en Desarrollo Multimedia y Web formado en el SENA contará con habilidades para realizar actividades como administración de proyectos, trabajo en equipo, interacción con clientes, un alto grado de liderazgo, autonomía y resiliencia a los cambios actuales.
    p El aprendiz de la Tecnología en Desarrollo Multimedia y Web, al finalizar su proceso de formación, podrá desempeñarse en ocupaciones y sectores para la creación y venta de software, contenido audiovisual, tanto en el plano presencial como en el plano digital, mercado que aporta desde diferentes aristas y en todas sus escalas.
    p #[strong ¡Bienvenidos!]


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p.mb-0 Los flujos de nuevas tecnologías llegan al país a un ritmo sin precedentes, haciendo que la demanda interna y las expectativas por nuevos productos y servicios se transformen con similar rapidez. De esta forma, la prospectiva de la industria TIC de los países menos desarrollados debe partir de la ubicación de la oferta nacional en el eje definido por las tensiones entre el mercado global y el mercado local, que operan como dos polos frente al tema. 
      br
      br
      | Esto significa identificar los focos tecnológicos prioritarios tanto a escala nacional como internacional, a partir de las fortalezas y debilidades del sector, con el fin de establecer el mercado objetivo. Teniendo en cuenta que estos evolucionan y se transforman continua y rápidamente, el talento humano en Colombia, formado en áreas de TI, se convierte en el determinante para afrontar los retos propuestos para el corto, mediano y largo plazo.
      br
      br
      | Es por ello que el SENA, busca a través de su Tecnología en Desarrollo Multimedia y Web, el ofrecer una integración de elementos de formación profesional, social, tecnológica y cultural, que aporten como elementos diferenciadores, sus metodologías y plataformas para el desarrollo de software de calidad, con acceso a tecnologías de última generación y una estructuración sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidaria y emprendedora, factores que lo acreditan y lo hacen pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias y cambios tecnológicos y las necesidades del sector empresarial y de los trabajadores, impactando positivamente la productividad, la competitividad, la equidad y el desarrollo del país.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias<br>a desarrollar

    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | Formular el proyecto multimedia de acuerdo con metodologías y documento de requisitos.
      li
        i.lista-ul__vineta
        | Elaborar proyecto multimedia de acuerdo con procedimientos técnicos.
      li
        i.lista-ul__vineta
        | Integrar elementos multimedia de acuerdo con técnicas y herramientas de producción digital.
      li
        i.lista-ul__vineta
        | Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social. 
      li
        i.lista-ul__vineta
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad.
      li
        i.lista-ul__vineta
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li
        i.lista-ul__vineta
        | Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
      li
        i.lista-ul__vineta
        | Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li
        i.lista-ul__vineta
        | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li
        i.lista-ul__vineta
        | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
      li
        i.lista-ul__vineta
        | Orientar investigación formativa según referentes técnicos.
      li
        i.lista-ul__vineta
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li
        i.lista-ul__vineta
        | Utilizar herramientas informáticas de acuerdo con necesidades de manejo de información.
      li
        i.lista-ul__vineta
        | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el marco común europeo de referencia para las lenguas. 

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil<br>de ingreso

    p Aspirante con mínimo nivel académico de media académica, grado 11° certificado. Edad mínima definida por la ley de 16 años. Título de bachiller o su equivalente validación aprobada por la entidad competente. Acreditar presentación del examen de estado de la educación media y los establecidos por el programa de formación.
  

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil<br>de egreso

    p El egresado del programa de formación Tecnología en Desarrollo Multimedia y Web, es talento humano formado integralmente por competencias relacionadas a apoyar y crear procesos y contenido multimedia con manejo de tecnologías en información y comunicación que constantemente necesitan actualización; generando una necesidad de presencia de profesionales y tecnólogos en sectores prioritarios, tanto a escala nacional como internacional, en áreas de mercadeo, publicidad y comunicaciones, para poder desempeñarse en el sector público y el privado. 
      br
      br
      | Podrá desempeñarse en ocupaciones y sectores para la creación y venta de software, contenido audiovisual, tanto en el plano presencial como en el plano digital, mercado que aporta desde diferentes aristas y en todas sus escalas.
      br
      br
      | El tecnólogo debe tener un alto sentido de responsabilidad, con capacidad para realizar actividades como administración de proyectos, trabajo en equipo, interacción con clientes, un alto grado de liderazgo, autonomía y resiliencia a los cambios actuales.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia<br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en talleres destinados a la combinación de práctica con conocimiento, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:     

    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | El instructor - Tutor
      li
        i.lista-ul__vineta
        | El entorno
      li
        i.lista-ul__vineta
        | las TIC
      li
        i.lista-ul__vineta
        | El trabajo colaborativo
  

          

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
