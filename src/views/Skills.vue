<template>
  <div class="skills d-flex justify-content-around align-items-center">
    <!-- <skills-txt/>
    <div class="animation"/> -->
  </div>
</template>

<script>
import SkillsTxt from "@/components/SkillsTxt"


export default {
  name: 'Skills',
  components: {
    SkillsTxt
  }
}
</script>

<style scoped>
.skills{
  width: 100%;
}
.animation{
  height: 30vh;
  width: 30vh
}
</style>
