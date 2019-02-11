<template>
  <div class="justify-content-center d-flex flex-column nav">
    <div class="d-flex flex-row navs">
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
      <div @click="active = !active" class="dropDownButton d-flex flex-column justify-content-around align-items-center">
        <span/>
        <span/>
        <span/>
      </div>
    </div>
    <div v-if="active" class="dropDownMenu d-flex flex-row justify-content-around">
      <router-link to="/" class="dropItem">
        <h3>Home</h3>
      </router-link>
      <span class="divider"/>
      <router-link to="/about" class="dropItem">
        <h3>About</h3>
      </router-link>
      <span class="divider"/>
      <router-link to="/skills" class="dropItem">
        <h3>Skills</h3>
      </router-link>
      <span class="divider"/>
      <router-link to="/projects" class="dropItem">
        <h3>Projects</h3>
      </router-link>
      <span class="divider"/>
      <router-link to="/contact" class="dropItem">
        <h3>Contact</h3>
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
  data: function() {
    return {
      active:false
    }

  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.dropDownButton{
  width: 3rem;
  height: 3rem;
  visibility: hidden;
  position: absolute;
  right: 1.5rem;
  top: 1.5rem;
  opacity: .7;
}
.dropDownButton span{
  width: 2rem;
  height: .5rem;
  background-color: #fbfdfe;
  border-radius: 15px;
}
.dropDownMenu{
  background-color: #f48668;
  width: 100%;
  border-top: 2px solid rgba(251, 253, 254, .5);
  position: relative;
  z-index: 10000;
  display: none !important;
}
.dropItem{
  margin: .5rem .5rem;
  color: #fbfdfe;
}
.nav{
  background-color: #f7c59f;
  z-index: 1;
}
.navs{
  max-width: 100%;
  flex-direction: column !important;
}
.navItem{
  padding: 2rem .5rem;
  color: #fbfdfe;
}
.divider{
  width: 2px;
  height: 100%;
  background-color: #fbfdfe;
  opacity: .5;
}
@media only screen and (max-width: 1070px) {
  .nav {
    flex-direction: row !important;
  }
  .navs {
    flex-direction: row !important;
  }
  .navItem{
    padding: 2.3rem 1.5rem;
  }
}
@media only screen and (max-width: 850px) {
  .dropDownButton{
    visibility: visible;
  }
  .navItem{
    visibility: hidden;
  }
  .dropDownMenu{
    display: flex !important;
  }
}
@media only screen and (max-width: 550px) {
  .dropItem h3{
    padding: .7rem 0rem;
    font-size: 1rem;
  }
}
@media only screen and (max-height: 768px) {
  .navItem{
    padding: 1rem 1.5rem;
  }
  .dropDownButton{
    height: 2.5rem;
    right: 1.5rem;
    top: 1rem;
    opacity: .7;
  }
}
</style>
