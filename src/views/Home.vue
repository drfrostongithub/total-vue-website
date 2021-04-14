<template>
  <div id="home">
    CSS IS COOL
    <img src="../assets/site.jpg" alt="site" />
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style lang="scss">
#home {
  img {
    max-width: -webkit-fill-available;
    opacity: 50%;
  }
}
</style>
