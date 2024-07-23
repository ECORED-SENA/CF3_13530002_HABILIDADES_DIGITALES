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
            img(src='@/assets/curso/tema3/img4.png', alt='1. Imagen que presenta cómo iniciar sesión en el correo de Outlook. 2. Imagen que presenta los puntos para ir a los servicios que ofrece el correo. 3. Imagen que presenta los servicios que ofrece el correo.').m-auto
          figure.d-block.d-lg-none(data-aos="fade-left")
            img(src='@/assets/curso/tema3/img4m.png', alt='1. Imagen que presenta cómo iniciar sesión en el correo de Outlook. 2. Imagen que presenta los puntos para ir a los servicios que ofrece el correo. 3. Imagen que presenta los servicios que ofrece el correo.').m-auto
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
                    p.text-white.mb-0 A continuación, responderemos a cada uno de los interrogantes.

          .row.justify-content-center.align-items-center          
            .col-lg-10                    
              p(data-aos="fade-right") Primero, revisemos cómo es el procedimiento con Google Drive:
              .tarjeta.tarjeta--gris1.mb-5.d-none.d-lg-block(data-aos="fade-right")
                .p-4
                  TabsC.color-acento-contenido
                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 1")
                      p Para crear una carpeta, se hace clic en el ícono de los puntos y se selecciona el ícono de #[span.txt-c1 Drive].


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 2")
                      p Luego, se da clic derecho y se selecciona la opción #[span.txt-c1 nueva carpeta].


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 3")
                      p Luego se selecciona el #[span.txt-c1 nombre de la carpeta].


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 4")
                      p Lo siguiente, es #[span.txt-c1 configurar la privacidad]. Para ello, se da clic derecho sobre la carpeta que se ha creado y se elige la opción compartir.


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 5")
                      p En la caja de texto se pueden ingresar las #[span.txt-c1 direcciones de correo electrónico] de las personas con quienes se desea compartir esa carpeta.


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 6")
                      p Posterior al ingreso del correo o correos de las personas con las que se desea compartir la información, se debe seleccionar el tipo de permiso que tendrán las personas con las que se ha compartido. Existen 3 tipos de permisos:                  
                      p #[b.txt-c1 Lector:] la persona puede ver los archivos dispuestos, pero no tiene posibilidad de modificar la información.      
                      p #[b.txt-c1 Comentador:] la persona puede ver los archivos y, adicionalmente, dejar comentarios en ellos, pero no puede modificarlos.              
                      p.mb-0 #[b.txt-c1 Creador:] la persona tiene acceso total para poder modificar la información, añadir archivos a la carpeta, entre otros.


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 7")
                      p Ahora, pensemos en que se necesita #[span.txt-c1 compartir la información con muchas personas]. Por ejemplo, si se trata de la carta del menú de uhacer en este caso? Se da clic derecho en la carpeta y se elige la parte inferior de la ventana que se despliega, y se da clic donde dice: obtener enlace.


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 8")
                      p Luego se despliega otra ventana donde se puedinalmente, se puede #[span.txt-c1 seleccionar el tipo de permiso] que, generalmente, es de lector.


                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 9")
                      p.mb-0 Para agregar archivos a la carpeta, simplemente arrástrelos desde su computador a la ventana del navegador donde está abierto Drive. Para compartirlo, solo necesita hacer clic derecho y seleccionar la opción para obtener el enlace, luego puede compartirlo a través de WhatsApp, correo electrónico o de la forma que desee.

            .col-lg-12.mb-5.d-block.d-lg-none

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 1
                p Para crear una carpeta, se hace clic en el ícono de los puntos y se selecciona el ícono de #[span.txt-c1 Drive].


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 2
                p Luego, se da clic derecho y se selecciona la opción #[span.txt-c1 nueva carpeta].


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 3
                p Luego se selecciona el #[span.txt-c1 nombre de la carpeta].


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 4
                p Lo siguiente, es #[span.txt-c1 configurar la privacidad]. Para ello, se da clic derecho sobre la carpeta que se ha creado y se elige la opción compartir.


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 5
                p En la caja de texto se pueden ingresar las #[span.txt-c1 direcciones de correo electrónico] de las personas con quienes se desea compartir esa carpeta.


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 6
                p Posterior al ingreso del correo o correos de las personas con las que se desea compartir la información, se debe seleccionar el tipo de permiso que tendrán las personas con las que se ha compartido. Existen 3 tipos de permisos:                  
                p #[b.txt-c1 Lector:] la persona puede ver los archivos dispuestos, pero no tiene posibilidad de modificar la información.      
                p #[b.txt-c1 Comentador:] la persona puede ver los archivos y, adicionalmente, dejar comentarios en ellos, pero no puede modificarlos.              
                p.mb-0 #[b.txt-c1 Creador:] la persona tiene acceso total para poder modificar la información, añadir archivos a la carpeta, entre otros.


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 7
                p Ahora, pensemos en que se necesita #[span.txt-c1 compartir la información con muchas personas]. Por ejemplo, si se trata de la carta del menú de uhacer en este caso? Se da clic derecho en la carpeta y se elige la parte inferior de la ventana que se despliega, y se da clic donde dice: obtener enlace.


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 8
                p Luego se despliega otra ventana donde se puedinalmente, se puede #[span.txt-c1 seleccionar el tipo de permiso] que, generalmente, es de lector.


              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 9
                p.mb-0 Para agregar archivos a la carpeta, simplemente arrástrelos desde su computador a la ventana del navegador donde está abierto Drive. Para compartirlo, solo necesita hacer clic derecho y seleccionar la opción para obtener el enlace, luego puede compartirlo a través de WhatsApp, correo electrónico o de la forma que desee.                                                        

          .row.justify-content-center.align-items-center          
            .col-lg-10 
              p(data-aos="fade-right") Continuemos con el servicio de Microsoft OneDrive:
              .tarjeta.tarjeta--gris1.d-none.d-lg-block(data-aos="fade-left")
                .p-4
                  TabsC.color-acento-contenido
                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 1")
                      p  Para acceder, inicie sesión en su correo electrónico y luego haga clic en los puntos de la esquina superior izquierda para #[span.txt-c1 ver el menú].

                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 2")
                      p Ya dentro de OneDrive se puede crear una carpeta nueva con el botón azul que dice #[span.txt-c1 “Agregar nuevo”] y, allí, seleccionar el tipo de archivo que se desea crear.
                        p.txt-c4.mb-0 Si se elige #[span.txt-c1 “Carpeta”], lo siguiente es ponerle un nombre.

                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 3")
                      p Posterior a esto, se da clic en la opción para #[span.txt-c1 compartir] y lo que sigue es indicar el correo electrónico de las personas a las que se desea dar #[span.txt-c1 acceso a la información].

                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 4")
                      p Ahora, para configurar los #[span.txt-c1 permisos], haga clic en el botón de arriba y luego puede elegir si la persona o personas con las que se ha compartido la carpeta pueden realizar modificaciones, haciendo clic en la casilla #[span.txt-c1 “Permitir modificaciones”].

                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 5")
                      p Si se desea compartir con muchas personas, se puede seleccionar la opción #[span.txt-c1 “Todos los usuarios”].

                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 6")
                      p Para añadir #[span.txt-c1 archivos a la carpeta] basta con #[span.txt-c1 arrastrarlos] desde el equipo hasta la ventana del navegador donde se tiene abierto el OneDrive.

                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 7")
                      p Para compartirlo, simplemente se le da clic en el botón de #[span.txt-c1 “Compartir”] y luego en #[span.txt-c1 “Compartir carpeta”]. 

                    
                    .tarjeta.color-acento-botones--borde.p-4.mb-4(titulo="Paso 8")
                      p Así se puede #[span.txt-c1 compartir el enlace] por WhatsApp, correo electrónico o el medio que se prefiera.

            .col-lg-12.d-block.d-lg-none 
              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 1              
                p  Para acceder, inicie sesión en su correo electrónico y luego haga clic en los puntos de la esquina superior izquierda para #[span.txt-c1 ver el menú].

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 2              
                p Ya dentro de OneDrive se puede crear una carpeta nueva con el botón azul que dice #[span.txt-c1 “Agregar nuevo”] y, allí, seleccionar el tipo de archivo que se desea crear.
                  p.txt-c4.mb-0 Si se elige #[span.txt-c1 “Carpeta”], lo siguiente es ponerle un nombre.

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 3              
                p Posterior a esto, se da clic en la opción para #[span.txt-c1 compartir] y lo que sigue es indicar el correo electrónico de las personas a las que se desea dar #[span.txt-c1 acceso a la información].

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 4             
                p Ahora, para configurar los #[span.txt-c1 permisos], haga clic en el botón de arriba y luego puede elegir si la persona o personas con las que se ha compartido la carpeta pueden realizar modificaciones, haciendo clic en la casilla #[span.txt-c1 “Permitir modificaciones”].

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 5              
                p Si se desea compartir con muchas personas, se puede seleccionar la opción #[span.txt-c1 “Todos los usuarios”].

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 6              
                p Para añadir #[span.txt-c1 archivos a la carpeta] basta con #[span.txt-c1 arrastrarlos] desde el equipo hasta la ventana del navegador donde se tiene abierto el OneDrive.

              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 7              
                p Para compartirlo, simplemente se le da clic en el botón de #[span.txt-c1 “Compartir”] y luego en #[span.txt-c1 “Compartir carpeta”]. 

              
              .tarjeta.color-acento-botones--borde.p-4.mb-4
                h5.txt-c1 Paso 8             
                p Así se puede #[span.txt-c1 compartir el enlace] por WhatsApp, correo electrónico o el medio que se prefiera.                                 


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
