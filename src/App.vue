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
$colourText: #353f44;
$colourHeading: #384548;
$colourNotification: #42bfdc;
$colourPositive: #34aa44;
$colourNegative: #f85359;

@mixin border-radius($radius) {
  -webkit-border-radius: $radius;
  -moz-border-radius: $radius;
  border-radius: $radius;
}
html,
body,
#KmanSoftwareCoreContainer {
  height: 100%;
  scroll-behavior: smooth;
}

body {
  background-color: #f5f5f5;
  margin: 0;
  padding: 0;
}

body,
p,
li,
input,
select {
  font-family: "Roboto", sans-serif;
  font-weight: 400;
  font-style: normal;
  color: $colourText;
}

a,
a:visited {
  text-decoration: none;
}

a:focus {
  outline: none;
}

b,
strong {
  font-weight: 700;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: canada-type-gibson, sans-serif;
  font-style: normal;
  color: $colourHeading;
}

h1,
h2,
h3,
h4 {
  font-weight: 400;
}

h5,
h6 {
  font-weight: 600;
}

input {
  &:focus {
    outline: none;
  }
}

small {
  font-size: 0.75rem;
}

.text-left {
  text-align: left;
}

.text-center {
  text-align: center;
}

.text-right {
  text-align: right;
}

.no-margin {
  margin: 0 !important;
}

.no-radius {
  border-radius: 0 !important;
}
</style>
