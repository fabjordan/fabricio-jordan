<template>
  <div>
    <section class="about-section" id="about-section">
      <b-container>
        <b-row class="d-flex mt-3">
          <b-col sm="12" xs="12" lg="6" class="col-img-responsive">
            <div class="about-img w-100"></div>
          </b-col>
          <b-col sm="12" xs="12" lg="6" class="about">
            <h1 class="big-font big-font-1 text-white">Sobre</h1>
            <h2 class="big-font big-font-2 mb-4">Sobre</h2>
            <p class="text-white bio">
              Full Stack Developer. Graduado em Ciências da Computação.
              Autodidata. Apaixonado por inovação, amante de video-games
              e do bom e velho Rock'n Roll!
            </p>
            <p class="text-white">
              Ingressei na graduação de Ciência da Computação com 16 anos. Passei a maior parte da minha carreira
              trabalhando com desenvolvimento de software focado na Web. Enquanto desenvolvedor, foquei em aprender boas
              práticas de desenvolvimento, clean code, arquitetura de microsserviços, gestão de projetos e outros.
            </p>
            <p class="text-white">
              Além de desenvolvedor, atuo com gestão de projetos e liderança de pequenas e médias equipes, com foco
              sempre na agregação de valor ao cliente e entrega de resultados.
            </p>

            <div class="social-container">
              <ul class="social-icons">
                <li>
                  <b-link title="Github" href="https://github.com/fabjordan" target="_blank">
                    <i class="fa fa-github"></i>
                  </b-link>
                </li>
                <li>
                  <b-link title="Linkedin" href="https://www.linkedin.com/in/fabricio-jordan/" target="_blank">
                    <i class="fa fa-linkedin"></i>
                  </b-link>
                </li>
                <li>
                  <b-link title="Instagram" href="https://www.instagram.com/fabricio__jordan/" target="_blank">
                    <i class="fa fa-instagram"></i>
                  </b-link>
                </li>
                <li>
                  <b-link title="Currículo" href="https://drive.google.com/file/d/14zJQxCFNDcHuqD-JRoqOs08AM2jcpD-7/view?usp=sharing" target="_blank">
                    <i class="fa fa-file-pdf-o"></i>
                  </b-link>
                </li>
              </ul>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  name: "About"
};
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";

.about-section {
  padding-bottom: 10%;

  @media screen and (min-width: $display-xs) and (max-width: $display-lg) {
    .bio {
      margin-top: 8% !important;
    }
  }

  .bio {
    margin-top: 10%;
  }

  .about-img {
    height: 500px;
    padding: 30px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    background-image: url("../assets/images/foto.jpeg");
  }

  .about-info li span:nth-child(1) {
    width: 90px;
  }

  .social-container {
    margin: 0;
    width: 100%;
    padding-top: 10px;

    .social-icons {
      padding: 0;
      list-style: none;

      li {
        font-size: 1.2em;
        position: relative;
        margin-right: 15px;
        display: inline-block;
      }

      i {
        top: 21px;
        left: 21px;
        color: $white;
        position: absolute;
        transition: all $timing ease-out;
      }

      a {
        display: inline-block;

        &:before {
          @include transformScale();
          content: " ";
          width: 60px;
          height: 60px;
          display: block;
          border-radius: 100%;
          transition: all $timing ease-out;
          background: linear-gradient(45deg, $iconColor, $accent);
        }

        &:hover:before {
          transform: scale(0);
          transition: all $timing ease-in;
        }

        &:hover i {
          @include transformScale(2.2);
          color: $iconColor;
          background: -webkit-linear-gradient(45deg, $iconColor, $accent);
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
          transition: all $timing ease-in;
        }
      }
    }
  }
}
</style>