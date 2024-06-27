<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Almacenamiento en la nube
    .row.mb-5
      .col-12.bg-c5(data-aos="fade-down")
        .row.align-items-center.justify-content-center
          .col-auto.px-0.d-none.d-md-block
            figure
              img(src='@/assets/curso/tema3/img1.svg', style="width:280px" alt='').m-auto
          .col(data-aos="fade-left")
            .p-4.p-md-0
              p.mb-0 #[span.txt-c2 ¿Conoce qué es el disquete? o ¿utilizó memorias USB?] #[span.text-white Realmente todo ha avanzado de manera sorprendente y, hoy en día, podemos almacenar información, incluso, en medios que no siempre necesitamos tener con nosotros; con un dispositivo con acceso a Internet y con una cuenta de correo electrónico, es suficiente para acceder a la información. Pero, ¿cómo funciona esto? El siguiente video nos explica esta temática:]
    figure(data-aos="fade-left")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/CQzx05c6Zvs" title="Almacenamiento" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    Separador
    #t_3_1
    .titulo-segundo.color-acento-contenido
      h2 3.1 Aplicaciones en la nube
    p.mb-0(data-aos="fade-right") Las cuentas de correo nos permiten acceder a múltiples servicios. En el caso de Chrome, solo se debe acceder al botón que, generalmente, se encuentra en la parte superior derecha, con nuestra cuenta y contraseña de correo electrónico.
    .row.bg-c12
      .col-12
        .p-5
          .row.mb-5
            .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
              figure
                img(src='@/assets/curso/tema3/img2.png', style="width:800px" ,alt='Imagen que presenta cómo se inicia sesión en Google Chrome.').m-auto
            .col-lg-5(data-aos="fade-left")
              figure
                img(src='@/assets/curso/tema3/img3.png', style="width:500px" ,alt='Imagen que presenta los puntos que presentan acceso a los servicios asociados a la cuenta de Google y la fotografía de perfil o la letra inicial del nombre asociado al correo.').m-auto
          .row.align-items-center.mb-3
            .col-auto(data-aos="fade-right")
              figure
                img(src='@/assets/curso/tema3/img2.svg', style="width:150px" ,alt='Icono de Google.').m-auto
            .col(data-aos="fade-left")
              p.mb-0 Otra manera de acceder a las aplicaciones de Google es iniciar sesión en el correo Gmail, en este caso se puede encontrar el botón de aplicaciones en la parte superior derecha del correo.
          p.mb-5(data-aos="fade-down") Otra opción puede ser Microsoft, que permite acceder a diferentes servicios desde la cuenta de correo de Outlook. Se inicia sesión con la cuenta de correo electrónico y se busca la opción de aplicaciones, representada por un botón en forma de pequeños botones agrupados en la parte superior izquierda del navegador. Al presionarlos, se puede interactuar con los servicios que ofrece.
          figure.d-none.d-lg-block(data-aos="fade-right")
            img(src='@/assets/curso/tema3/img4.png', alt='1. Imagen que presenta cómo iniciar sesión en el correo de Outlook. 2. Imgen que presenta los puntos para ir a los servicios que ofrece el correo. 3. Imagen que presenta los servicios que ofrece el correo.').m-auto
          figure.d-block.d-lg-none(data-aos="fade-left")
            img(src='@/assets/curso/tema3/img4m.png', alt='1. Imagen que presenta cómo iniciar sesión en el correo de Outlook. 2. Imgen que presenta los puntos para ir a los servicios que ofrece el correo. 3. Imagen que presenta los servicios que ofrece el correo.').m-auto
          Separador
          #t_3_2
          .titulo-segundo.color-acento-contenido
            h2 3.2 Gestión de información en la nube
          p.mb-5(data-aos="fade-right") Al tener claro cuáles son los servicios más conocidos de almacenamiento en la nube, surgen los siguientes interrogantes:
          .row.justify-content-center.mb-5
            .col-lg-8.bg-c13(data-aos="fade-down")
              .row.align-items-center.justify-content-center
                .col-auto.px-0.d-none.d-md-block
                  figure
                    img(src='@/assets/curso/tema3/img3.svg', style="width:300px" alt='').m-auto
                .col(data-aos="fade-left")
                  .p-4.p-md-0
                    p.text-white.mb-0 #[b ¿Cómo puedo usarlos?]
                    p.text-white #[b ¿Cómo configuro la privacidad de mi información?]
                    p.text-white.mb-0 A continuación responderemos a cada uno de los interrogantes.
          p.mb-5(data-aos="fade-right") Primero, revisemos cómo es el procedimiento con Google Drive:
          .tarjeta.tarjeta--gris1.mb-5(data-aos="fade-right")
            .p-5
              PasosB.color-acento-contenido
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Para crear una carpeta, se hace clic en el ícono de los puntos y se selecciona el ícono de #[span.txt-c2 Drive].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img6.png', style="width:240px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Luego, se da clic derecho y se selecciona la opción #[span.txt-c2 nueva carpeta].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img7.png', style="width:240px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Luego se selecciona el #[span.txt-c2 nombre de la carpeta].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img8.png', style="width:240px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Lo siguiente, es #[span.txt-c2 configurar la privacidad]. Para ello, se da clic derecho sobre la carpeta que se ha creado y se elige la opción compartir.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img9.png', style="width:350px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 En la caja de texto se pueden ingresar las #[span.txt-c2 direcciones de correo electrónico] de las personas con quienes se desea compartir esa carpeta.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img10.png', style="width:300px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-6.mb-4.mb-lg-0
                    p.txt-c4 Posterior al ingreso del correo o correos de las personas con las que se desea compartir la información, se debe seleccionar el tipo de permiso que tendrán las personas con las que se ha compartido. Existen 3 tipos de permisos:
                    p.txt-c4 #[b.txt-c2 Lector:] la persona puede ver los archivos dispuestos, pero no tiene posibilidad de modificar la información. 
                    p.txt-c4 #[b.txt-c2 Comentador:] la persona puede ver los archivos y, adicionalmente, dejar comentarios en ellos, pero no puede modificarlos.
                    p.txt-c4.mb-0 #[b.txt-c2 Creador:] la persona tiene acceso total para poder modificar la información, añadir archivos a la carpeta, entre otros.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img11.png', style="width:200px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Ahora, pensemos en que se necesita #[span.txt-c2 compartir la información con muchas personas]. Por ejemplo, si se trata de la carta del menú de un restaurante. 
                    p.txt-c4 ¿Qué hacer en este caso? Se da clic derecho en la carpeta y se elige la parte inferior de la ventana que se despliega, y se da clic donde dice: obtener enlace.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img12.png', style="width:300px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Luego se despliega otra ventana donde se puede elegir la opción.
                    p.txt-c4 Finalmente, se puede #[span.txt-c2 seleccionar el tipo de permiso] que, generalmente, es de lector.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img13.png', style="width:300px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Para agregar archivos a la carpeta, simplemente arrástrelos desde su computador a la ventana del navegador donde está abierto Drive. Para compartirlo, solo necesita hacer clic derecho y seleccionar la opción para obtener el enlace, luego puede compartirlo a través de WhatsApp, correo electrónico o de la forma que desee.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img14.png', style="width:400px", alt='').m-auto
          p.mb-5(data-aos="fade-right") Continuemos con el servicio de Microsoft OneDrive:
          .tarjeta.tarjeta--gris1(data-aos="fade-left")
            .p-5
              PasosB.color-acento-contenido
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Para acceder, inicie sesión en su correo electrónico y luego haga clic en los puntos de la esquina superior izquierda para #[span.txt-c2 ver el menú].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img15.png', style="width:300px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4 Ya dentro de OneDrive se puede crear una carpeta nueva con el botón azul que dice #[span.txt-c2 “Agregar nuevo”] y, allí, seleccionar el tipo de archivo que se desea crear.
                    p.txt-c4.mb-0 Si se elige #[span.txt-c2 “Carpeta”], lo siguiente es ponerle un nombre.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img16.png', style="width:320px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Posterior a esto, se da clic en la opción para #[span.txt-c2 compartir] y lo que sigue es indicar el correo electrónico de las personas a las que se desea dar #[span.txt-c2 acceso a la información].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img17.png', style="width:320px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Ahora, para configurar los #[span.txt-c2 permisos], haga clic en el botón de arriba y luego puede elegir si la persona o personas con las que se ha compartido la carpeta pueden realizar modificaciones, haciendo clic en la casilla #[span.txt-c2 “Permitir modificaciones”].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img18.png', style="width:320px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Si se desea compartir con muchas personas, se puede seleccionar la opción #[span.txt-c2 “Todos los usuarios”].
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img19.png', style="width:320px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Para añadir #[span.txt-c2 archivos a la carpeta] basta con #[span.txt-c2 arrastrarlos] desde el equipo hasta la ventana del navegador donde se tiene abierto el OneDrive.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img20.png', style="width:300px", alt='').m-auto
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Para compartirlo, simplemente se le da clic en el botón de #[span.txt-c2 “Compartir”] y luego en #[span.txt-c2 “Compartir carpeta”]. 
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img21.png', style="width:300px", alt='').m-auto
                
                .row.justify-content-center.align-items-center(titulo="")
                  .col-lg-4.mb-4.mb-lg-0
                    p.txt-c4.mb-0 Así se puede #[span.txt-c2 compartir el enlace] por WhatsApp, correo electrónico o el medio que se prefiera.
                  .col-lg-auto
                    figure
                      img(src='@/assets/curso/tema3/img22.png', style="width:350px", alt='').m-auto

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
