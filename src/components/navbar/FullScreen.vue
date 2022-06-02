<template>
  <div>
    <div ref="myNav" class="overlay">
      <a class="closebtn" @click="closeNav()">&times;</a>

      <div class="overlay-content">
        <b-nav-item href="#home-section" @click="closeNav()">Início</b-nav-item>
        <b-nav-item href="#about-section" @click="closeNav()">Sobre</b-nav-item>
        <b-nav-item href="#techs-section" @click="closeNav()">Tecnologias</b-nav-item>
        <b-nav-item href="#experiences" @click="closeNav()">Timeline</b-nav-item>
        <b-nav-item href="#contact-section" @click="closeNav()">Contato</b-nav-item>
      </div>
    </div>

    <b-link class="openbtn" @click="openNav()">
      <span class="navbar-toggler-icon"></span>
    </b-link>
  </div>
</template>

<script>
export default {
  name: "FullScreen",
  methods: {
    closeNav() {
      this.$refs.myNav.style.width = "0%";
    },
    openNav() {
      this.$refs.myNav.style.width = "100%";
    }
  }
};
</script>

<style scoped lang="scss">
@import "../../assets/scss/_variables.scss";

.openbtn {
  cursor: pointer;
  font-size: 20px;

  &:hover {
    font-size: 25px;
    transition: 0.5s;
  }
}

.overlay {
  top: 0;
  left: 0;
  width: 0;
  z-index: 1;
  height: 100%;
  position: fixed;
  transition: 0.5s;
  overflow-x: hidden;
  background-color: $black-rgb;
  background-color: $black-rgba;

  .overlay-content {
    top: 25%;
    width: 100%;
    margin-top: 30px;
    text-align: center;
    position: relative;
    list-style-type:none;
  }

  a {
    padding: 8px;
    color: $gray-1;
    display: block;
    font-size: 36px;
    transition: 0.3s;
    text-decoration: none;
    transition: opacity .5s;

    &:hover {
      color: $white-1;
    }

    &:focus {
      color: $white-1;
    }
  }

  .closebtn {
    top: 20px;
    right: 45px;
    cursor: pointer;
    font-size: 60px;
    position: absolute;
  }
}
</style>