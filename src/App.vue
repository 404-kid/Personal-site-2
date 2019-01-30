<template>
  <div id="app">
    <!-- <Banner/> -->
    <Nav/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Nav from "@/components/Nav"
import Banner from "@/components/Banner"
import Footer from "@/components/Footer"

export default {
  components: {
    Nav,
    Banner,
    Footer
  }
}
</script>

<style>
</style>
