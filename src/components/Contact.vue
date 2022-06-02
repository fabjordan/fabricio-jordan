<template>
  <div>
    <section class="contact-section" id="contact-section">
      <b-container>
        <b-row class="mt-5 pb-5">
          <b-col>
            <h1 class="big-font big-font-1 text-white">Contate-me</h1>
            <h2 class="big-font big-font-2 mb-4">Contate-me</h2>
          </b-col>
        </b-row>
        <b-row class="d-flex">
          <b-col md="12" sm="12" xs="12" class="mb-5">
            <div class="bg-1 rounded card-body">
              <div class="mt-3">
                <p class="text-white">
                  Você pode entrar em contato comigo através do seguinte e-mail: 
                  <b>fabriciomonte2014@gmail.com</b>
                </p>

                <p class="text-white">
                  Se preferir, minhas redes sociais estão logo abaixo 😉
                </p>

                <hr style="border: 1px solid #555" class="mt-5" />

                <ul class="list-group list-group-horizontal w-100 bg-1 text-center mt-4">
                  <li class="list-group-item bg-none text-muted w-100">
                    <h2>
                      <b-link title="Github" href="https://github.com/fabjordan" target="_blank">
                        <i class="fa fa-github"></i>
                      </b-link>
                    </h2>
                  </li>
                  <li class="list-group-item bg-none text-muted w-100">
                    <h2>
                      <b-link title="Linkedin" href="https://www.linkedin.com/in/fabricio-jordan/" target="_blank">
                        <i class="fa fa-linkedin"></i>
                      </b-link>
                    </h2>
                  </li>
                  <li class="list-group-item bg-none text-muted w-100">
                    <h2>
                      <b-link title="Instagram" href="https://www.instagram.com/fabricio__jordan/" target="_blank">
                        <i class="fa fa-instagram"></i>
                      </b-link>
                    </h2>
                  </li>
                  <li class="list-group-item bg-none text-muted w-100">
                    <h2>
                      <b-link title="Currículo" href="https://drive.google.com/file/d/14zJQxCFNDcHuqD-JRoqOs08AM2jcpD-7/view?usp=sharing" target="_blank">
                        <i class="fa fa-file-pdf-o"></i>
                      </b-link>
                    </h2>
                  </li>
                </ul>

                <div class="col mt-3 text-center">
                  <span class="text-muted">" What I can't create I don't understand "</span>
                  <p class="text-muted">- Richard P. Feynman -</p>
                </div>
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
  name: "Contact"
};
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";
</style>