<template>
  <div class="home d-flex justify-content-around align-items-center">
    <HomeTxt class="big"/>
    <BLarge class="big"/>
    <b-mobile class="small"/>
    <home-txt-mobile class="small"/>
  </div>
</template>

<script>
import HomeTxt from "@/components/HomeTxt"
import BLarge from "@/components/BLarge"
import BMobile from "@/components/BMobile"
import HomeTxtMobile from "@/components/HomeTxtMobile"
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    HomeTxt,
    BLarge,
    BMobile,
    HomeTxtMobile
  }
}
</script>

<style scoped>
.home{
  width: 100%;
  height: 100%;
}
.small{
  display:none;
}
@media only screen and (max-width: 1070px) {
  .big{
    display:none;
  }
  .small{
    display:block;
  }
  .home{
    flex-direction: column !important;
    width: 100%;
  }
}

</style>
