<template>
  <div class="home d-flex justify-content-between align-items-center">
    <HomeTxt/>
    <BLarge/>
  </div>
</template>

<script>
import HomeTxt from "@/components/HomeTxt"
import BLarge from "@/components/BLarge"
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    HomeTxt,
    BLarge
  }
}
</script>

<style scoped>
.home{
  width: 100%;
}
</style>
