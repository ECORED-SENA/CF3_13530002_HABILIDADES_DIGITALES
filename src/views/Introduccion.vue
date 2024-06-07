<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.mb-4
      .col-lg-4.mb-4.mb-lg-0
        figure(data-aos="fade-right")
          img(src='@/assets/curso/intro/img1.png', style="width:350px" alt='').m-auto
      .col-lg-8
        .row.align-items-center.mb-3
          .col-lg-9.mb-4.mb-lg-0(data-aos="fade-right")
            .p-4.bg-c1
              p Vivimos en una era donde la tecnología ha transformado radicalmente la manera en que nos comunicamos, compartimos información y almacenamos nuestros datos. En este componente formativo, exploraremos tres pilares fundamentales de la vida digital moderna:
              ul.lista-ul.mb-0
                li.d-flex
                  i.fas.fa-code(style="color:#8722E2")
                  |
                  p.mb-0 #[b Correo electrónico:] el pionero de la comunicación digital.
                li.d-flex
                  i.fas.fa-code(style="color:#8722E2")
                  |
                  p.mb-0 #[b Redes sociales:] la revolución de las conexiones humanas.
                li.d-flex
                  i.fas.fa-code(style="color:#8722E2")
                  |
                  p.mb-0 #[b Almacenamiento en la nube:] la evolución del espacio digital.
          .col-lg-3(data-aos="fade-left")
            figure
              img(src='@/assets/curso/intro/img1.svg', style="width:180px" alt='').m-auto
        p.mb-0(data-aos="fade-down") Cada uno de estos elementos ha jugado un papel crucial en la configuración del entorno digital actual, facilitando la conexión global y redefiniendo nuestras interacciones cotidianas.
    .row 
      .col-12
        .p-4.bg-c2(data-aos="fade-right")
          .row 
            .col-12 
              .p-4.bg-c3
                .row.align-items-center.justify-content-center
                  .col-lg-6.mb-4.mb-lg-0
                    p A lo largo de este componente formativo, desentrañaremos las complejidades y ventajas de estos tres elementos clave del mundo digital, proporcionando una visión integral de cómo están moldeando nuestras vidas y transformando el panorama tecnológico global. 
                    p.txt-c1.mb-0 #[b Muchos éxitos en este proceso de aprendizaje.]
                  .col-lg-4
                    figure
                      img(src='@/assets/curso/intro/img2.png', style="width:350px" alt='').m-auto
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
