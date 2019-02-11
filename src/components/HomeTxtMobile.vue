<template>
  <div class="mobleTxt">
    <div class="circleBox">
      <div class="circles">
        <div class="circle circles"/>
        <div class="circle2 circles"/>
        <div class="circle3 circles"/>
        <div class="circle4 circles"/>
      </div>
    </div>
    <div class="wrds">
      <p class="lrg">Job Smith</p>
      <p class="lrg">Web Developer</p>
      <p class="sml">Full-stack Developer / Vue.js / Data Visualization</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeTxtMobile"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.mobleTxt{
  position: absolute;
  top: 20vh;
  z-index: 0;
}
p {
  z-index: 1;
  position: relative;
  z-index: 10;
  color: #fbfdfe;
}
.wrds {
  padding: 1rem;
  
}
.circleBox {
  position: relative;
}
.lrg {
  font-size: 6vw;
  line-height: normal;
  animation-name: wrdAnim;
  animation-duration: 3s;
  animation-iteration-count: 1;
  text-align: center;
}
.sml {
  font-size: 3.3vw;
  animation-name: wrdAnim;
  animation-duration: 3s;
  animation-iteration-count: 1;
  text-align: center;
}
.circles{
  position: absolute;
  background-color: #f7c59f;
  border-radius: 50%;
  z-index: 0;
  animation-duration: 1.25s;
  animation-iteration-count: 1;
}
.circle {
  height: 40vw;
  width: 40vw;
  top: -3vw;
  left: -4vw;
  animation-name: C1Anim;
}
.circle2 {
  height: 33vw;
  width: 33vw;
  top: 0vw;
  left: 24vw;
  animation-name: C2Anim;
}
.circle3 {
  height: 27vw;
  width: 27vw;
  top: 5vw;
  left: 50vw;
  animation-name: C3Anim;
}
.circle4 {
  height: 23vw;
  width: 23vw;
  top: 9vw;
  left: 40vw;
  animation-name: C4Anim;
}
@keyframes C4Anim {
  0% {
    top: -50vw;
    left: 100vw;
  }
  100% {
    top: 9vw;
    left: 40vw;
  }
}
@keyframes C3Anim {
  0% {
    top: 100vw;
    left: 70vw;
  }
  100% {
    top: 5vw;
    left: 50vw;
  }
}
@keyframes C2Anim {
  0% {
    top: 30vw;
    left: -10vw;
  }
  100% {
    top: 0vw;
    left: 24vw;
  }
}
@keyframes C1Anim {
  0% {
    top: -70vw;
    left: -10vw;
  }
  100% {
    top: -3vw;
    left: -4vw;
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
@media only screen and (max-width: 570px) {
  .circle{
    width: 14rem;
    height: 14rem;
  }
  .circle2{
    width: 11.8rem;
    height: 11.8rem;
    
  }
  .circle3{
    width: 9.8rem;
    height: 9.8rem;
  }
  .circle4{
    width: 8.3rem;
    height: 8.3rem;
  }
  .lrg{
    padding-top: 1rem;
    font-size: 2.2rem
  }
  .sml{
    visibility: hidden;
  }
}
@media only screen and (max-height: 768px) {
  .mobleTxt{
    top: 30vh;
  }
}
</style>
