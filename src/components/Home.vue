<template>
  <div>
    <section class="home-section" id="home-section">
      <b-container>
        <b-row class="first-row first d-flex align-items-center">
          <b-col lg="6" md="6" sm="12" xs="12" class="big-font pt-4">
            <h2 class="text-primary">Olá, meu nome é</h2>
            <h1 class="text-muted max-size">Fabrício Jordan</h1>
          </b-col>

          <b-col lg="6" md="6" sm="12" xs="12" class="pt-4">
            <h4 class="text-white">Full Stack Developer</h4>
            <hr style="border: 1px solid #555" />
            <h4 class="text-primary">Eu crio expressivas, modernas e elegantes aplicações para a Web</h4>

            <ul class="list-group list-group-horizontal w-100 bg-1 text-center mt-4">
              <li class="list-group-item bg-none text-muted w-100">
                <h2>
                  <b-link href="https://github.com/fabjordan" target="_blank">
                    <i class="fa fa-github"></i>
                  </b-link>
                </h2>
              </li>
              <li class="list-group-item bg-none text-muted w-100">
                <h2>
                  <b-link href="https://www.linkedin.com/in/fabricio-jordan/" target="_blank">
                    <i class="fa fa-linkedin"></i>
                  </b-link>
                </h2>
              </li>
              <li class="list-group-item bg-none text-muted w-100">
                <h2>
                  <b-link href="https://www.instagram.com/fabricio__jordan/" target="_blank">
                    <i class="fa fa-instagram"></i>
                  </b-link>
                </h2>
              </li>
            </ul>
          </b-col>
        </b-row>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped lang="scss">
@import "../assets/scss/_variables.scss";

.home-section {
  height: 600px;

  &:after {
    content: "";
    background: url("../assets/images/world.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    opacity: 0.04;
    height: 100%;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    position: absolute;
    z-index: -1;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  .first {
    margin-top: 10%;
  }
  .max-size {
    font-size: 5rem;
    font-weight: 1000;
  }
}
</style>