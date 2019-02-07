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
  position: absolute;
  transform: rotate(328deg);
  left: 25vw;
  top: 120vw;
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
@media only screen and (max-width: 1270px) {
  .b-design{
    top: 87vw
  }
}
@media only screen and (max-width: 970px) {
  .b-design{
    top: 90vw
  }
}
@media only screen and (max-width: 770px) {   
  .b-design{
    top: 110vw
  }
}
@media only screen and (max-width: 625px) {
  .b-design{
    top: 65vh
  }
  /* .B{
    font-size: 27rem;
  }
  #b1{
    left: 1.4rem;
  }
  #b2{
    left: 3.9rem;
  }
  #b3{
    left: 6.4rem;
  } */

}
</style>
