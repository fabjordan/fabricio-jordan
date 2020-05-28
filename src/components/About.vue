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

            <div class="bg-1 rounded">
              <ul class="about-info mt-2 pl-2 p-3 text-white">
                <li class="d-flex mb-3">
                  <span>Nome:</span>
                  <span>Fabrício Jordan</span>
                </li>
                <li class="d-flex mb-3">
                  <span>E-mail:</span>
                  <span>fabriciomonte2014@gmail.com</span>
                </li>
                <li class="d-flex mb-3">
                  <span>Phone:</span>
                  <span>(98) 98462-3100</span>
                </li>
                <li class="d-flex mb-3">
                  <span>Mora em:</span>
                  <span>São Luís / MA</span>
                </li>
              </ul>
            </div>

            <div class="social-container">
              <ul class="social-icons">
                <li>
                  <b-link href="https://www.instagram.com/fabricio__jordan/" target="_blank">
                    <i class="fa fa-instagram"></i>
                  </b-link>
                </li>
                <li>
                  <b-link href="https://www.linkedin.com/in/fabricio-jordan/" target="_blank">
                    <i class="fa fa-linkedin"></i>
                  </b-link>
                </li>
                <li>
                  <b-link href="https://github.com/fabjordan" target="_blank">
                    <i class="fa fa-github"></i>
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
  @media screen and (min-width: $display-xs) and (max-width: $display-lg) {
    .bio {
      margin-top: 8% !important;
    }
  }

  .bio {
    margin-top: 15%;
  }

  .about-img {
    height: 500px;
    padding: 30px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    background-image: url("../assets/images/foto3.jpg");
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