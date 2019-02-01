<template>
  <div class="justify-content-center d-flex flex-column nav">
    <router-link to="/" class="navItem">
      <h3>Home</h3>
    </router-link>
    <router-link to="/about" class="navItem">
      <h3>About</h3>
    </router-link>
    <router-link to="/skills" class="navItem">
      <h3>Skills</h3>
    </router-link>
    <router-link to="/projects" class="navItem">
      <h3>Projects</h3>
    </router-link>
    <router-link to="/contact" class="navItem">
      <h3>Contact</h3>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "Nav"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav{
  background-color: #f7c59f
}
.navItem{
  padding: 1.5rem .5rem;
  color: #fbfdfe;
}

</style>
