<template>
  <div class="b-design">
    <p id="b1">B</p>
    <p id="b2">B</p>
    <p id="b3">B</p>
  </div>
</template>

<script>
export default {
  name: "BLarge"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.b-design {
  /* height: 20rem;
  width: 30rem; */
  transform: rotate(328deg);
  height: 35%;
  width: 35vw;
}
#b1 {
  position: absolute;
  margin: 0rem;
  font-size: 60rem;
  color: #f48668;
  left: -10rem;
}
#b2 {
  position: absolute;
  margin: 0rem;
  font-size: 60rem;
  color: #6f8597;
  left: -5.6rem;
  animation-name: wrdAnim;
  animation-duration: 2s;
  animation-iteration-count: 1;
}
#b3 {
  position: absolute;
  margin: 0rem;
  font-size: 60rem;
  color: #fbfdfe;
  left: 0rem;
  animation-name: wrdAnim;
  animation-duration: 2s;
  animation-iteration-count: 1;
}
@keyframes wrdAnim {
  0% {
    left: -10rem;
  }
  100% {
    left: 5;
  }
}
@media only screen and (max-width: 1800px) {
  #b1 {
    font-size: 50rem;
    left: -5rem;
  }
  #b2 {
    font-size: 50rem;
    left: -0.7rem;
  }
  #b3 {
    font-size: 50rem;
    left: 3.6rem;
  }
  @keyframes wrdAnim {
    0% {
      left: -5rem;
    }
    100% {
      left: 5;
    }
  }
}
@media only screen and (max-width: 1600px) {
  #b1 {
    font-size: 40rem;
    left: -3rem;
  }
  #b2 {
    font-size: 40rem;
    left: 0.7rem;
  }
  #b3 {
    font-size: 40rem;
    left: 4.5rem;
  }
  @keyframes wrdAnim {
    0% {
      left: -3rem;
    }
    100% {
      left: 5;
    }
  }
}
@media only screen and (max-width: 1270px) {
  #b1 {
    font-size: 30rem;
    left: 0rem;
    top: 7rem;
  }
  #b2 {
    font-size: 30rem;
    left: 2.8rem;
    top: 7rem;
  }
  #b3 {
    font-size: 30rem;
    left: 5.6rem;
    top: 7rem;
  }
  @keyframes wrdAnim {
    0% {
      left: 0rem;
    }
    100% {
      left: 5;
    }
  }
}
@media only screen and (max-width: 1070px) {
  .b-design {
    height: 0%;
    width: 0%;
  }
}
</style>
