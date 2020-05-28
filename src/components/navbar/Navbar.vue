<template>
  <div>
    <b-navbar toggleable type="dark">
      <b-navbar-brand href="#">
        <b-img :src="require('../../../public/logo.svg')" loading="lazy" width="200"></b-img>
      </b-navbar-brand>

      <FullScreen />
    </b-navbar>
  </div>
</template>

<script>
import FullScreen from "./FullScreen";

export default {
  name: "Navbar",
  components: {
    FullScreen
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../../assets/scss/_variables.scss";

@media (min-width: $display-md) {
  .navbar {
    padding: 1rem 5rem;
  }
}
</style>
