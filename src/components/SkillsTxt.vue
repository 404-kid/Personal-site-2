<template>
<div class="about">
  <div class="wrds">
    <p class="lrg">Skills</p>
    <p class="sml">As a Full-Stack Developer my skills are varied, as they cover almost all aspects of Web Development in some way. However I have a few areas of expertise in component based front end frameworks (like React or Vue), 2D and 3D dynamic data visualization and animation, and instant client to client communication.</p>
    <p class="sml">Some of the Tech I use: JavaScript, HTML, CSS, Vue.js, Nuxt, Vuex, Vue Native, React, React Native, Canvas, WebGL. Three.js, Express.js, BootStrap, Node.js, Socket.io, PostgreSQL, MySQL, Knex.js, Electron, Heroku, AWS.</p>
  </div>
  <div class="circle"/>
  <div class="circle2"/>
  <div class="circle3"/>
  <div class="circle4"/>
  <div class="circle5"/>
</div>
</template>

<script>
export default {
  name: "SkillsTxt",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about{
  max-width: 40%;
}
p {
  z-index: 1;
  position: relative;
  z-index: 10;
  color: #fbfdfe;
}
.lrg {
  font-size: 5rem;
  line-height: normal;
  animation-name: wrdAnim;
  animation-duration: 1.5s;
  animation-iteration-count: 1;
  color: #e88d67;
  margin-bottom: 3rem;
}
.sml {
  font-size: 1.5rem;
  line-height: normal;
  animation-name: wrdAnimS;
  animation-duration: 1.5s;
  animation-iteration-count: 1;
   margin-bottom: 3rem;
}
.circle{
  position: absolute;
  height: 20rem;
  width: 20rem;
  background-color: #6f8597;
  border-radius: 50%;
  z-index: 0;
  top: 6rem;
  left: 20rem;
  animation-name: C1Anim;
  animation-duration: .75s;
  animation-iteration-count: 1;
}
.circle2{
  position: absolute;
  height: 25rem;
  width: 25rem;
  background-color: #6f8597;
  border-radius: 50%;
  z-index: 0;
  top: 16rem;
  left: 9rem;
  animation-name: C2Anim;
  animation-duration: .75s;
  animation-iteration-count: 1;
}
.circle3{
  position: absolute;
  height: 18rem;
  width: 18rem;
  background-color: #6f8597;
  border-radius: 50%;
  z-index: 0;
  top: 21rem;
  left: 30rem;
  animation-name: C3Anim;
  animation-duration: .75s;
  animation-iteration-count: 1;
}
.circle4{
  position: absolute;
  height: 15rem;
  width: 15rem;
  background-color: #6f8597;
  border-radius: 50%;
  z-index: 0;
  top: 1rem;
  left: 9rem;
  animation-name: C4Anim;
  animation-duration: .75s;
  animation-iteration-count: 1;
}
.circle5{
  position: absolute;
  height: 15rem;
  width: 15rem;
  background-color: #6f8597;
  border-radius: 50%;
  z-index: 0;
  top: 10rem;
  left: 8rem;
  animation-name: C5Anim;
  animation-duration: .75s;
  animation-iteration-count: 1;
}
@keyframes C5Anim {
  0%   {top: -10%; left: -30%}
  100% {top: 10rem; left: 8rem;}
}
@keyframes C4Anim {
  0%   {top: -10%; left: -30%}
  100% {top: 1rem; left: 9rem;}
}
@keyframes C3Anim {
  0%   {top: 100%; left: 70%}
  100% {top: 21rem; left: 30rem;}
}
@keyframes C2Anim {
  0%   {top: 30%; left: -10%}
  100% {top: 16rem; left: 9rem;}
}
@keyframes C1Anim {
  0%   {top: -70%; left: -10%}
  100% {top: 6rem; left: 20rem;}
}
@keyframes wrdAnim {
  0%   {color: rgba(0, 0, 0, 0);}
  25%   {color: rgba(0, 0, 0, 0);}
  45%   {color: rgba(0, 0, 0, 0);}
  100% {color:#e88d67;}
}
@keyframes wrdAnimS {
  0%   {color: rgba(0, 0, 0, 0);}
  25%   {color: rgba(0, 0, 0, 0);}
  45%   {color: rgba(0, 0, 0, 0);}
  100% {color:#fbfdfe;}
}

</style>
