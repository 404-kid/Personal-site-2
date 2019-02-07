<template>
  <router-link to="/" class="b-design">
    <p id="b1">B</p>
    <p id="b2">B</p>
    <p id="b3">B</p>
  </router-link>
</template>

<script>
export default {
  name: "BSmall"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.b-design{
  position: absolute;
  left: 15px;
  top: 40px;
  z-index: 10;
}
#b1{
  position: absolute;
  font-size: 100px;
  color: #f48668;
}
#b2{
  position: absolute;
  font-size: 100px;
  left: 9px;
  color: #6f8597;
}
#b3{
  position: absolute;
  font-size: 100px;
  left: 18px;
  color: #fbfdfe;
}
</style>
