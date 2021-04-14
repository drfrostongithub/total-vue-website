<template>
  <body>
    <Navbar />
    <router-view />
    <Footer />
  </body>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap");

$image-path: "~@/../mdb/mdbvue/img";
@import "~@/../mdb/mdbvue/scss/mdb-free.scss";

:root {
  scroll-behavior: smooth;
  font-size: 16px;
  --text-primary: #b6b6b6;
  --text-secondary: #ececec;
  --bg-primary: #23232e;
  --bg-secondary: #141418;
}
</style>
