<template>
  <div class="about d-flex justify-content-around align-items-center">
    <about-txt class="w-50"/>
    <profile-pic/>
  </div>
</template>

<script>
import AboutTxt from "@/components/AboutTxt"
import ProfilePic from "@/components/ProfilePic"

export default {
  name: 'About',
  components: {
    AboutTxt,
    ProfilePic
  }
}
</script>

<style scoped>
.about{
  width: 100%;
  height: 100%;
}
</style>
