<template>
  <div id="app">
    <HelloWorld />
    <Body />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.2.0/css/all.css"
      integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ"
      crossorigin="anonymous"
    />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Body from "./components/Body.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Body,
  },
};
</script>

<style>
@font-face {
  font-family: SFBold;
  src: url(./assets/font/SanFranciscoDisplay-Bold.otf);
}
@font-face {
  font-family: SFBlack;
  src: url(./assets/font/SanFranciscoDisplay-Black.otf);
}
@font-face {
  font-family: SFHeavy;
  src: url(./assets/font/SanFranciscoDisplay-Heavy.otf);
}
@font-face {
  font-family: SFRegular;
  src: url(./assets/font/SanFranciscoDisplay-Regular.otf);
}
@font-face {
  font-family: SFMedium;
  src: url(./assets/font/SanFranciscoDisplay-Medium.otf);
}
@font-face {
  font-family: SFSemibold;
  src: url(./assets/font/SanFranciscoDisplay-Semibold.otf);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  padding: 0 0;
  font-size: 100%;
}
</style>
