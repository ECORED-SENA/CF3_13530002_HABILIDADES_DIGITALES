<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Redes sociales
    p.mb-5(data-aos="fade-right") Para aprender qué son las redes sociales y cuáles son las más populares, lo invitamos a consultar el siguiente video.
    figure.mb-5(data-aos="fade-left")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/5GeY76vb_oo" title="Redes sociales" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mb-5
      .col-lg-7.order-2.order-lg-1(data-aos="fade-right")
        p El uso de las redes sociales, ha sido absorbido por las personas en todo el mundo, y hoy ya es parte de la rutina.
        .row.align-items-center.mb-3
          .col-md-auto
            figure
              img(src='@/assets/curso/tema2/img1.svg', style="width:150px" alt='').m-auto
          .col
            p.mb-0 Representan las relaciones que se dan a través de una estructura social, que se ha ido conformando a través de un conjunto de personas que se relacionan entre ellas en diferentes contextos.
        p.mb-0 Esto hizo de esos espacios, un lugar donde las marcas y las empresas también quieren estar para interactuar con sus prospectos y clientes, trayendo posibilidades muy positivas, como:
      .col-lg-5.mb-4.mb-lg-0.order-1.order-lg-2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/img1.png', style="width:450px" alt='').m-auto
    .row.align-items-center
      .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/img2.png', style="width:280px" alt='').m-auto
      .col-lg-9(data-aos="fade-left")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Compartir la visión de la empresa")
            .col-12
              p.mb-0 Las redes sociales son una especie de escaparate, donde se puede mostrar la visión del negocio, y lo que ofrece.
          .row(titulo="La personalización del mensaje")
            .col-12
              p La personalización del mensaje y la interacción directa con el cliente. 
              p.mb-0 En las redes sociales, es posible tener una relación mucho más personalizada y directa con cada cliente o posible cliente, debido a que se puede entrar en contacto con cada uno, ya sea para resolver alguna situación, o para descubrir nuevas informaciones.
          .row(titulo="Posibilidad de segmentación del público")
            .col-12
              p.mb-0 Al publicar en redes sociales, es posible segmentar los posteos (#[i posts]), de acuerdo con las características de la audiencia, para dirigir los esfuerzos hacia aquellos rangos de público que posee más afinidad con la oferta, para llegar a una solución.
          .row(titulo="Saber más sobre cada uno de los clientes")
            .col-12
              p.mb-0 Recordar que las personas comparten sus gustos, deseos y otras informaciones que pueden ser valiosas para las empresas, a la hora de acercarse a su público objetivo; es por esta razón que hay que estar alerta a lo que es relevante para la audiencia, para así poder conectarse mejor con ella.
    .row.align-items-center.mb-5
      .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Posibilidad de vender a través de estos canales")
            .col-12
              p.mb-0 Así como es posible la relación con el público a través de las redes sociales, también es posible utilizarlas para vender productos o servicios; esto es importante si se aborda la audiencia con la que ya se tiene una relación que ha madurado lo suficiente, para incentivarla hacia una compra inteligente.
          .row(titulo="Crear un entorno controlado por la marca")
            .col-12
              p.mb-0 Si importar cual es el público al que se tiene acceso, este siempre se va a encontrar en algún tipo de red social.
          .row(titulo="Información en tiempo real")
            .col-12
              p.mb-0 Las redes sociales permiten comunicar mensajes a la menor brevedad posible. Para los canales oficiales o gubernamentales, es importante en el caso de una gestión de crisis.
          .row(titulo="Posibilidad de divulgació")
            .col-12
              p Posibilidad de divulgación para empresas con bajo presupuesto. 
              p.mb-0 Anunciar en las redes sociales, tiene un costo más bajo que en los medios tradicionales. Adicionalmente, las redes permiten medir los resultados de las publicaciones, de una manera más fácil.
      .col-lg-3(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/img3.png', style="width:280px" alt='').m-auto
    p.mb-5(data-aos="fade-down") Se puede pensar que todas las redes sociales son iguales, pero esto no es así. Por lo general, están divididas en diferentes tipos, de acuerdo con el objetivo de los usuarios al crear el perfil. Una sociedad puede tener más de un tipo de red. La clasificación más común es la siguiente:
    .row.mb-5
      .col-12
        .p-4.p-lg-5.bg-c8(data-aos="fade-left")
          .tarjeta.tarjeta--azul1
            .p-4.p-lg-5
              SlyderA(tipo="b")
                .row.align-items-center.justify-content-center
                  .col-lg-6.mb-4.mb-lg-0
                    p.mb-0 #[b Red social de relaciones]
                    p ¿El propósito de las redes sociales no es justamente relacionarse? 
                    p Ese es el objetivo de la mayoría, pero no todas están enfocadas en ese objetivo.
                    p.mb-0 El caso más conocido es Facebook, cuyo propósito, al menos al concebirse, fue el de conectar personas. Hay muchas más redes que, a la larga, también encajan en otros objetivos, como Instagram, LinkedIn, Twitter, Google+, etc.
                  .col-lg-5
                    figure
                      img(src='@/assets/curso/tema2/img5.png', style="width:380px" alt='').m-auto
                .row.align-items-center.justify-content-center
                  .col-lg-6.mb-4.mb-lg-0
                    p.mb-0 #[b Red social de entretenimiento]
                    p Las redes sociales de entretenimiento, son aquellas cuyo objetivo principal no es relacionarse con las personas, sino consumir contenido. 
                    p El ejemplo más icónico es YouTube, la mayor plataforma de distribución de videos en el mundo, cuyo objetivo es ver y publicar videos.
                    p.mb-0 Otro caso es Pinterest, donde las personas publican y consumen imágenes.
                  .col-lg-5
                    figure
                      img(src='@/assets/curso/tema2/img6.png', style="width:380px" alt='').m-auto
                .row.align-items-center.justify-content-center
                  .col-lg-6.mb-4.mb-lg-0
                    p.mb-0 #[b Red social profesional]
                    p Estas son las redes en las que los usuarios tienen como objetivo, crear relaciones profesionales con otros usuarios, divulgar proyectos y conquistas profesionales, presentar su curriculum y habilidades, como también adquirir indicaciones, empleos, etc. 
                    p.mb-0 LinkedIn es la red social profession al más conocida y utilizada, pero existen otras que vienen conquistando espacio, como: Bebee, Bayt, Xing y Viadeo. Otras redes que no son exclusivamente profesionales, también se han utilizado para este fin, como Facebook, Instagram, YouTube, X anteriormente llamada Twitter y Pinterest.
                  .col-lg-5
                    figure
                      img(src='@/assets/curso/tema2/img7.png', style="width:380px" alt='').m-auto
                .row.align-items-center.justify-content-center
                  .col-lg-6.mb-4.mb-lg-0
                    p.mb-0 #[b Red social de nicho]
                    p Las redes sociales de nicho, son las que están dirigidas a un público específico, ya sea una categoría profesional o personas que tienen un interés específico en común. 
                    p Una de estas redes es la de TripAdvisor, donde los usuarios aportan notas y comentarios a temas relacionados con el sector gastronómico y turístico.
                    p.mb-0 Otros casos son DevianArt o Behance, comunidades en las que artistas visuales promueven sus trabajos. También existe Goodreads, una red social para lectores, quienes pueden hacer reseñas de libros y también recomendarlos.
                  .col-lg-5
                    figure
                      img(src='@/assets/curso/tema2/img8.png', style="width:380px" alt='').m-auto
    .row.bg-c9
      .col-12
        .px-5.pt-5
          .row.mb-4
            .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
              .p-4.bg-c2.h-100
                p.mb-0 Las redes sociales aportan infinidad de oportunidades; una de ellas es la de pertenecer a una comunidad que no tiene una locación física, solo tienen un perfil y un interés en común: permiten compartir información con cualquier persona en este mundo digital; esta nueva tecnología derrumbó los paradigmas de la comunicación masiva.
            .col-lg-4.mb-4.mb-lg-0(data-aos="fade-down")
              figure
                img(src='@/assets/curso/tema2/img10.png', style="width:380px" alt='').m-auto
            .col-lg-4.mb-4.mb-lg-0(data-aos="fade-left")
              .p-4.bg-c10.h-100
                p.mb-0 Las redes sociales cuentan con millones de usuarios, muchos de ellos poseen cualidades y características para crear contenido e influenciar a sus seguidores, y así logran ser famosos, creciendo en la medida en que los siguen y compartiendo sus contenidos; esto los hace atractivos para grandes marcas que impulsan sus productos a través de los influenciadores y sus canales digitales.
          .row.align-items-center.mb-3
            .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
              figure
                img(src='@/assets/curso/tema2/img11.png', style="width:380px" alt='').m-auto
            .col-lg-8(data-aos="fade-left")
              .row.mb-4
                .col-auto.d-none.d-lg-block
                  figure
                    img(src='@/assets/curso/tema2/img2.svg', style="width:100px" alt='').m-auto
                .col
                  p.mb-0 Si se desea fama y poder, entonces se deben crear contenidos que atraigan a muchas personas con gustos similares. Ejemplo: un docente crea contenido digital para acercar el conocimiento a sus aprendices en tiempos de pandemia; una causa noble como apoyar a miles de víctimas en la guerra; afinidades deportivas y otros contextos, que permitan conocer y relacionarse con personas de diferentes partes del mundo.
              .row.mb-4
                .col-12
                  .p-4.bg-c7
                    .row.align-items-center
                      .col-md-auto.mb-4.mb-md-0
                        figure
                          img(src='@/assets/curso/tema2/img3.svg', style="width:80px" alt='').m-auto
                      .col
                        p.mb-0 Es importante conocer varios conceptos como: seguridad, privacidad y normas básicas de comportamiento en la Internet (netiqueta), que son análogos con las comunidades y redes sociales en la Internet.
              p.mb-0 Las redes sociales conectan a millones de personas y son capaces de incrementar o no la popularidad de un candidato político, o viralizar un evento o un contenido digital. Se puede decir que están presentes en nuestra vida cotidiana, pasando por nuestra intimidad, hasta llegar a influenciar en la toma de algunas decisiones relacionadas con la política, la educación o, simplemente, con nuestra apariencia física. De ahí la importancia de conocer los riesgos que se tienen al pertenecer a estas comunidades digitales.
          p.mb-5(data-aos="fade-right") A continuación, haremos referencia a algunos de estos riesgos porque, al identificarlos, sabremos qué precauciones tomar para evitar convertirse en una víctima.
          .row
            .col-12
              .p-4.p-lg-5.bg-c8(data-aos="fade-left")
                .tarjeta.tarjeta--azul1
                  .p-4.p-lg-5
                    SlyderA(tipo="b")
                      .row.align-items-center.justify-content-center
                        .col-lg-6.mb-4.mb-lg-0
                          p.mb-0 #[b Suplantación de identidad digital]
                          p Suplantar la identidad, en las redes sociales, se presenta cuando un usuario toma el nombre, cuentas o la información personal de otro usuario, para hacerse pasar por él.
                          p.mb-0 Estos son delincuentes que utilizan perfiles falsos, con el nombre y fotografía del perjudicado, con el objetivo de realizar delitos como la estafa, la extorsión, el chantaje, entre otros.
                        .col-lg-5
                          figure
                            img(src='@/assets/curso/tema2/img12.png', style="width:380px" alt='').m-auto
                      .row.align-items-center.justify-content-center
                        .col-lg-6.mb-4.mb-lg-0
                          p.mb-0 #[b Fraude, #[i phishing] y #[i malware]]
                          p.mb-0 Los cibercriminales usan mensajes directos o publicaciones tentadoras con enlaces maliciosos o de #[i phishing] que, a su vez, contienen #[i malware]. Incluso, teniendo las configuraciones de seguridad pertinentes, no estamos 100 % seguros de estas amenazas. Lo mejor es verificar la veracidad del mensaje, observando al remitente, así como tener presente que las entidades bancarias no solicitan información personal, ni de cuentas, por medio de correos electrónicos.
                        .col-lg-5
                          figure
                            img(src='@/assets/curso/tema2/img13.png', style="width:380px" alt='').m-auto
                      .row.align-items-center.justify-content-center
                        .col-lg-6.mb-4.mb-lg-0
                          p.mb-0 #[b #[i Ciberbullying] o acoso cibernético]
                          p.mb-0 Este delito es uno de los más peligrosos; llega a maltrato o agresión a través de texto, voz o fotos, en formatos de video y audio, subidos a las redes sociales. Afecta a millones de personas (especialmente a los jóvenes) alrededor del mundo y preocupa a profesionales de la salud.
                        .col-lg-5
                          figure
                            img(src='@/assets/curso/tema2/img14.png', style="width:380px" alt='').m-auto
                      .row.align-items-center.justify-content-center
                        .col-lg-6.mb-4.mb-lg-0
                          p.mb-0 #[b Violaciones, secuestros o raptos con fines de explotación sexual (#[i Grooming])]
                          p.mb-0 Millones de personas son víctimas de delitos cibernéticos, siendo los niños los más vulnerables, cuando se encuentran solos en casa y tienen acceso a Internet desde su celular, computadora, o hasta una consola de videojuegos, porque estos medios pueden ser utilizados por delincuentes para ganarse la confianza de los niños a través de un perfil falso en las redes, para entablar conversaciones y luego pedirles fotografías o videos, violentando así la inocencia de los niños. Esta problemática resulta muy preocupante y peligrosa, por lo que es importante saber tomar las medidas necesarias y evitar los riesgos de esta situación.
                        .col-lg-5
                          figure
                            img(src='@/assets/curso/tema2/img15.png', style="width:380px" alt='').m-auto
                      .row.align-items-center.justify-content-center
                        .col-lg-6.mb-4.mb-lg-0
                          p.mb-0 #[b Problemas legales]
                          p.mb-0 Internet y especialmente, las redes sociales, nos permiten expresarnos libremente. Sin embargo, algunas personas no se dan cuenta de que cualquier cosa que se diga o publique en las redes sociales, puede tener implicaciones legales. Por esta razón, debemos tener mucho cuidado con insultar, difamar o difundir falsos rumores. Dichos contenidos pueden generar problemas relacionados con la protección de datos personales (habeas data), propiedad industrial e intelectual, derecho penal y derechos de la personalidad, derecho laboral y la publicidad, entre otros.
                        .col-lg-5
                          figure
                            img(src='@/assets/curso/tema2/img16.png', style="width:380px" alt='').m-auto
    Separador
    #t_2_1
    .titulo-segundo.color-acento-contenido
      h2 2.1 Recomendaciones para el uso de redes sociales
    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        .p-4.bg-c2.h-100
          p.mb-0 Las redes sociales no solo se han convertido en una herramienta para interactuar con las personas, sino para potenciar el desarrollo empresarial y apoyar el proceso educativo, entre muchas otras aplicaciones. Pero existen consideraciones importantes que se deben tener en cuenta a la hora de utilizarlas.
      .col-lg-3.mb-4.mb-lg-0(data-aos="fade-up")
        figure
          img(src='@/assets/curso/tema2/img17.png', style="width:380px" alt='').m-auto
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-left")
        .p-4.bg-c10.h-100
          figure.mb-3
            img(src='@/assets/curso/tema2/img4.svg', style="width:80px" alt='')
          p.mb-0 Existen 3 pilares dentro de la seguridad de la información, los cuales son fundamentales en el momento de comprender la ciberseguridad. Esta triada está compuesta por la confidencialidad, la disponibilidad y la integridad.
    .row.align-items-center
      .col-lg-3.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/img18.png', style="width:280px" alt='').m-auto
      .col-lg-9(data-aos="fade-left")
        p Las siguientes recomendaciones son de gran ayuda para cuando se realice la creación de un perfil en redes sociales y se evite cualquier posible robo de identidad.
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Utilice una contraseña segura")
            .col-12
              p Utilice una contraseña segura, no deje accesibilidad a los delincuentes digitales. Muchas veces se utilizan contraseñas como #[b 12345678] o #[b pepito1234] y, prácticamente, “dejamos las llaves pegadas en la puerta”, esperando que nadie ingrese a nuestro hogar. Lo recomendable es combinar mayúsculas, minúsculas, símbolos y números; procurar que tenga más de 12 caracteres. 
              p.mb-0 #[b Por ejemplo:]
              p.mb-0 #[b Int3ntotenerClave2egur4]
          .row(titulo="Configure la privacidad en las redes sociales")
            .col-12
              p Esta es una opción que nos brindan las diferentes plataformas, al gestionar nuestro perfil. Utilizar esta posibilidad para evitar la exposición de la información y que otras personas puedan hacer uso indebido de nuestros datos.
              p.mb-0 Como ejemplo, en Facebook, para poder configurar las diferentes opciones de privacidad, se debe ir al menú Configuración/Privacidad. Una vez allí, se puede revisar opción por opción, para activar o seleccionar la que mejor se ajuste al perfil que se quiere crear.
    .row.align-items-center.mb-5
      .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Piense antes de publicar")
            .col-12
              p En muchos casos, las redes sociales son fuente interminable de información y es, básicamente, porque no calculamos los alcances de lo que publicamos. En temas de seguridad, brindamos información con una simple fotografía, con la dirección de nuestra casa, compartimos la emoción de nuestro auto nuevo, sin proteger la placa o, en un comentario, indicamos nuestra ubicación.
              p.mb-0 Toda esta información puede ser tomada por delincuentes quienes se mantienen al acecho; inclusive, existen empresas que observan y analizan en Facebook, el perfil del candidato que van a contratar.
          .row(titulo="Cuidado con los contenidos sospechosos")
            .col-12
              p.mb-0 Los delincuentes crean cualquier tipo de artimaña para obtener su información, juegan con las ilusiones de sus víctimas, ofreciendo premios, viajes o dinero, por medio de enlaces enviados a los correos, o invitaciones en las redes sociales a concursos que carecen de veracidad; tanto, que debemos pensar en el adagio popular que dice “de esto tan bueno no dan tanto”.
          .row(titulo="Huella digital")
            .col-12
              p.mb-0 Este es el rastro que dejan las personas al hacer uso de Internet, como gustos, hobbies, correos o información bancaria.
      .col-lg-3(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/img19.png', style="width:280px" alt='').m-auto
    .row.mb-5
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        .p-4.bg-c2.h-100
          .row
            .col-auto
              figure
                img(src='@/assets/curso/tema2/img5.svg', style="width:80px" alt='')
            .col
              p.mb-0 Lo invitamos a consultar el video #[b Conoce estos 5 consejos para proteger tu identidad digital], el cual se encuentra en el material complementario y explica tips para proteger su identidad digital.
      .col-lg-3.mb-4.mb-lg-0(data-aos="fade-down")
        figure
          img(src='@/assets/curso/tema2/img6.svg', style="width:380px" alt='').m-auto
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-left")
        .p-4.bg-c11.h-100
          p.text-white.mb-0 Estas, son solo algunas de las recomendaciones que debemos seguir para crear nuestro perfil un poco más seguro, pero el único responsable de lo que se publica, de lo que se comparte o no, es usted mismo. Piense e identifique estrategias para no ser víctima de los delincuentes digitales.
    .row
      .col-auto(data-aos="fade-right")
        p.txt-c3.mb-0 Gracias a la huella digital, se pueden detectar amenazas y los responsables de las mismas.

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
