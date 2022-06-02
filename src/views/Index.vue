<template>
  <div class="page">
    <Navbar></Navbar>
    <Home></Home>
    <About></About>
    <Techs></Techs>
    <Experience></Experience>
    <Contact></Contact>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/navbar/Navbar";
import Home from "@/components/Home";
import About from "@/components/About";
import Techs from "@/components/Techs";
import Contact from "@/components/Contact";
import Experience from "../components/Experience.vue";

export default {
  name: "Index",
  components: {
    Navbar,
    Home,
    About,
    Techs,
    Contact,
    Experience
}
};
</script>

<style lang="scss">
</style>