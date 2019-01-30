<template>
  <div class="d-flex flex-row justify-content-around bg-dark">
    <router-link to="/" class="nav-link"><h3>Home</h3></router-link>
    <router-link to="/portfolio" class="nav-link"><h3>Portfolio</h3></router-link>
    <router-link to="/blog" class="nav-link"><h3>Blog</h3></router-link>
    <router-link to="/contact" class="nav-link"><h3>Contact</h3></router-link>
  </div>
</template>

<script>
export default {
  name: 'Nav',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
