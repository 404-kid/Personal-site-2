<template>
  <div class="b-design">
    <p id="b1" class="B">B</p>
    <p id="b2" class="B">B</p>
    <p id="b3" class="B">B</p>
  </div>
</template>

<script>
export default {
  name: "BMobile"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.b-design {
  position: fixed;
  transform: rotate(328deg);
  left: 25vw;
  bottom: 15vw;
  z-index: 10;
}
.B{
  font-size: 70vw;
  animation-name: wrdAnim;
  animation-duration: 2s;
  animation-iteration-count: 1;
  position: absolute;
  margin: 0rem;
  z-index: 10;
  width: 0%;
  height: 0%;
}
#b1 {
  color: #f48668;
  left: 3.5vw;

}
#b2 {
  color: #6f8597;
  left: 10vw;

}
#b3 {
  color: #fbfdfe;
  left: 16.5vw;

}
@keyframes wrdAnim {
  0% {
    top: 0;
    left: 0;
  }
  100% {
    top: 0;
    left: 3.7;
  }
}
@media only screen and (max-height: 1366px) {
  .b-design{
    bottom: 18vw;
  }
}
@media only screen and (max-width: 770px) {   
  .b-design{
    bottom: 25vw;
  }
}
@media only screen and (max-width: 625px) {
  .b-design{
    bottom: 30vw;
  }
}
@media only screen and (max-width: 500px) {
  .b-design{
    bottom: 40vw;
  }
}
@media only screen and (max-height: 768px) {
  .b-design{
    z-index: -1;
  }
}
@media only screen 
  and (min-width: 1024px) 
  and (max-height: 1366px) 
  and (orientation: portrait) 
  and (-webkit-min-device-pixel-ratio: 1.5) {
  .b-design{
    bottom: 35vw;
  }
}
</style>
