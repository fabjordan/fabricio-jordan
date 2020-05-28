<template>
  <div>
    <section class="techs-section" id="techs-section">
      <b-container>
        <b-row class="mt-5 pb-5">
          <b-col>
            <h1 class="big-font big-font-1 text-white">Tecnologias Favoritas</h1>
            <h2 class="big-font big-font-2 mb-4">Tecnologias Favoritas</h2>
          </b-col>
        </b-row>
        <b-row class="d-flex mt-5">
          <b-col md="6" sm="6" xs="12" class="mb-5">
            <div class="bg-1 p-2 rounded card-body">
              <div class="text-center mt-1 h-img d-flex justify-content-center">
                <b-img
                  :src="require('../assets/images/laravel.svg')"
                  class="img-fluid"
                  alt
                  width="60"
                ></b-img>
              </div>
              <div class="mt-2">
                <h5 class="text-white text-center">Laravel Framework</h5>
                <p class="text-white mt-2 p-3">
                  Laravel é um framework PHP muito popular no mundo inteiro por fornecer soluções
                  elegantes para as necessidades comuns de desenvolvimento de sistemas web.
                </p>
              </div>
            </div>
          </b-col>

          <b-col md="6" sm="6" xs="12" class="mb-5">
            <div class="bg-1 p-2 rounded card-body">
              <div class="text-center mt-1 h-img d-flex justify-content-center">
                <b-img
                  :src="require('../assets/images/docker.svg')"
                  class="img-fluid"
                  alt
                  width="80"
                ></b-img>
              </div>
              <div class="mt-2">
                <h5 class="text-white text-center">Docker</h5>
                <p class="text-white mt-2 p-3">
                  Docker é uma plataforma de software que permite a criação,
                  o teste e a implantação de aplicações rapidamente criando pacotes de software
                  em unidades padronizadas (containers).
                </p>
              </div>
            </div>
          </b-col>

          <b-col md="6" sm="6" xs="12" class="mb-5">
            <div class="bg-1 p-2 rounded card-body">
              <div class="text-center mt-1 h-img d-flex justify-content-center">
                <b-img
                  :src="require('../assets/images/nodejs.svg')"
                  class="img-fluid"
                  alt
                  width="100"
                ></b-img>
              </div>
              <div class="mt-2">
                <h5 class="text-white text-center">Node.JS</h5>
                <p class="text-white mt-2 p-3">
                  Node.js é uma plataforma construída sobre o motor JavaScript do Google Chrome
                  para facilmente construir aplicações de rede rápidas e escaláveis.
                </p>
              </div>
            </div>
          </b-col>

          <b-col md="6" sm="6" xs="12" class="mb-5">
            <div class="bg-1 p-2 rounded card-body">
              <div class="text-center mt-1 h-img d-flex justify-content-center">
                <b-img :src="require('../assets/images/vue.svg')" class="img-fluid" alt width="70"></b-img>
              </div>
              <div class="mt-2">
                <h5 class="text-white text-center">Vue.JS</h5>
                <p class="text-white mt-2 p-3">
                  Vue é um framework progressivo para a construção de interfaces de usuário.
                  Vue foi projetado desde sua concepção para ser adotável incrementalmente.
                </p>
              </div>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  name: "Techs"
};
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";

.techs-section {
  padding-bottom: 10%;

  .card-body {
    @media screen and (min-width: $display-sm) and (max-width: $display-lg) {
      height: 400px;
    }

    .h-img {
      height: 100px !important;
    }
  }
}
</style>