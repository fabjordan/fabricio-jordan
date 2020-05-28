<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
// @import url("https://fonts.googleapis.com/css2?family=Balsamiq+Sans:wght@400;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@900&display=swap");
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.css");

*,
*::before,
*::after {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

html {
  line-height: 1.15;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
  -ms-overflow-style: scrollbar;
  -webkit-tap-highlight-color: rgba(3, 3, 3, 0);
}

body {
  // font-family: 'Balsamiq Sans', cursive !important;
  font-family: "Quicksand", sans-serif !important;
  background-color: #111115 !important;
}
</style>