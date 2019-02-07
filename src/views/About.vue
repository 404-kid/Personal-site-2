<template>
  <div class="about d-flex justify-content-around align-items-center">
    <about-txt/>
    <div class="profilePic" alt="Personal picture"/>
  </div>
</template>

<script>
import AboutTxt from "@/components/AboutTxt"

export default {
  name: 'About',
  components: {
    AboutTxt
  }
}
</script>

<style scoped>
.profilePic{
  height: 40rem;
  width: 40rem;
  border-radius: 50%;
  background-image: url("../assets/pic.png");
  background-position: center;
}
.about{
  width: 100%;
}
</style>
