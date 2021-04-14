<template>
  <div id="Navbar">
    <nav class="navbar">
      <div class="container-fluid">
        <nav class="breadcrumb" aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="/">Home</a></li>
            <li class="breadcrumb-item active" aria-current="page">
              <a href="#">Data</a>
            </li>
            <li class="breadcrumb-item"><a href="/about">About</a></li>
          </ol>
        </nav>
      </div>
    </nav>
    <div class="belowNav">
      <marquee>Total Cipta Persada</marquee>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  components: {},
};
</script>
<style lang="scss">
#Navbar {
  .breadcrumb {
    display: flex;
    margin: auto;
  }
}
</style>
