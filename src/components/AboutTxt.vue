<template>
  <div>
    <div class="circleBox">
        <div class="circle circles"/>
        <div class="circle2 circles"/>
        <div class="circle3 circles"/>
    </div>
    <div class="wrds">
      <p class="lrg">About Me</p>
      <p class="sml">A dual citizen of the U.K and the U.S, I’ve been fortunate enough to travel. Currently I am based out of Denver, CO. My truest passion lies in creating things that amaze others mostly that takes the form of creating Web Apps. I have a particular disposition towards creating 2D and 3D animations.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutTxt"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p {
  z-index: 1;
  position: relative;
  z-index: 10;
  color: #fbfdfe;
}
.wrds {
  padding: 3rem;
  width: 80%
}
.circleBox {
  position: relative;
}
.lrg {
  font-size: 6rem;
  line-height: normal;
  animation-name: wrdAnim2;
  animation-duration: 3s;
  animation-iteration-count: 1;
  color: #e88d67;
}
.sml {
  padding-left: 2rem;
  font-size: 2.5rem;
  animation-name: wrdAnim;
  animation-duration: 3s;
  animation-iteration-count: 1;
  line-height: 130%;
}
.circles{
  position: absolute;
  background-color: #6f8597;
  border-radius: 50%;
  z-index: 1;
  animation-duration: 1.25s;
  animation-iteration-count: 1;
}
.circle {
  height: 45rem;
  width: 45rem;
  top: -5rem;
  left: 0rem;
  animation-name: C1Anim;
}
.circle2 {
  height: 30rem;
  width: 30rem;
  top: 20rem;
  left: 0rem;
  animation-name: C2Anim;
}
.circle3 {
  height: 28rem;
  width: 28rem;
  top: 19rem;
  left: 23rem;
  animation-name: C3Anim;
}
@keyframes C1Anim {
  0% {
    top: -100vh;
    left: -10vw;
  }
  100% {
    top: -5rem;
    left: 0rem;
  }
}
@keyframes C2Anim {
  0% {
    top: 130vh;
    left: -40vw;
  }
  100% {
    top: 20rem;
    left: 0rem;
  }
}
@keyframes C3Anim {
  0% {
    top: 100vh;
    left: 70vw;
  }
  100% {
    top: 19rem;
    left: 23rem;
  }
}
@keyframes wrdAnim {
  0% {
    color: rgba(0, 0, 0, 0);
  }
  25% {
    color: rgba(0, 0, 0, 0);
  }
  45% {
    color: rgba(0, 0, 0, 0);
  }
  100% {
    color: #fbfdfe;
  }
}
@keyframes wrdAnim2 {
  0% {
    color: rgba(0, 0, 0, 0);
  }
  25% {
    color: rgba(0, 0, 0, 0);
  }
  45% {
    color: rgba(0, 0, 0, 0);
  }
  100% {
    color: #e88d67;
  }
}
@media only screen and (max-width: 1800px) {
  .lrg {
    font-size: 5.5rem;
  }
  .sml{
    font-size: 2.3rem;
  }
  .circle {
    height: 40rem;
    width: 40rem;
  }
  .circle2 {
    height: 30rem;
    width: 30rem;
  }
  .circle3 {
    height: 25rem;
    width: 25rem;
  }
}
@media only screen and (max-width: 1600px) {
  .lrg {
    font-size: 5.5rem;
  }
  .circle {
    height: 35rem;
    width: 35rem;
    top: -6rem;
    left: -1rem;
  }
  .circle2 {
    height: 27rem;
    width: 27rem;
    top: 13rem;
    left: -1rem;
  }
  .circle3 {
    height: 23rem;
    width: 23rem;
    top: 17rem;
    left: 22rem;
  }
@keyframes C1Anim {
  0% {
    top: -100vh;
    left: -10vw;
  }
  100% {
    top: -6rem;
    left: -1rem;
  }
}
@keyframes C2Anim {
  0% {
    top: 130vh;
    left: -40vw;
  }
  100% {
    top: 13rem;
    left: -1rem;
  }
}
@keyframes C3Anim {
  0% {
    top: 100vh;
    left: 70vw;
  }
  100% {
    top: 17rem;
    left: 22rem;
  }
}
}
@media only screen and (max-width: 1400px) {
  .lrg {
    font-size: 5rem;
  }
  .sml{
    font-size: 1.7rem;
  }
  .circle {
    height: 31rem;
    width: 31rem;
    top: -5rem;
    left: -1rem;
  }
  .circle2 {
    top: 12rem;
    left: -.5rem;
    height: 25rem;
    width: 25rem;
  }
  .circle3 {
    height: 21rem;
    width: 21rem;
    top: 15rem;
    left: 17rem;
  }
@keyframes C1Anim {
  0% {
    top: -100vh;
    left: -10vw;
  }
  100% {
    top: -5rem;
    left: -1rem;
  }
}
@keyframes C2Anim {
  0% {
    top: 130vh;
    left: -40vw;
  }
  100% {
    top: 12rem;
    left: -.5rem;
  }
}
@keyframes C3Anim {
  0% {
    top: 100vh;
    left: 70vw;
  }
  100% {
    top: 15rem;
    left: 17rem;
  }
}
}
@media only screen and (max-width: 1270px) {
  .lrg {
    font-size: 4.5rem;
  }
  .sml{
    font-size: 1.3rem;
  }
  .circle {
    height: 27rem;
    width: 27rem;
    top: -5rem;
    left: 0rem;
  }
  .circle2 {
    top: 9rem;
    left: -1.5rem;
    height: 23rem;
    width: 23rem;
  }
  .circle3 {
    height: 18rem;
    width: 18rem;
    top: 13rem;
    left: 15rem;
  }
@keyframes C1Anim {
  0% {
    top: -100vh;
    left: -10vw;
  }
  100% {
    top: -5rem;
    left: 0rem;
  }
}
@keyframes C2Anim {
  0% {
    top: 130vh;
    left: -40vw;
  }
  100% {
    top: 9rem;
    left: -1.5rem;
  }
}
@keyframes C3Anim {
  0% {
    top: 100vh;
    left: 70vw;
  }
  100% {
    top: 13rem;
    left: 15rem;
  }
}
}

</style>
