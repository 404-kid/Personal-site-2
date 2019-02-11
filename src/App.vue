<template>
  <div class="full container-fluid ">
    <BSmall/>
    <div id="app" class="d-flex flex-row">
      <Nav/>
      <router-view/>
    </div>
  </div>
</template>

<script>
import Nav from "@/components/Nav";
import BSmall from "@/components/BSmall";

export default {
  components: {
    Nav,
    BSmall
  }
};
</script>

<style>
.full{
  padding: 0px !important;
  background-color: #f4e9d9;
  height: 100vh;
}
#app {
  background-color: #f4e9d9;
  height: 100%;
  width: 100%;
}
html {
  background-size: contain;
  overflow: hidden !important;
  min-width: 100%;
  height: 100%;
}
html, body {
  overflow-x: hidden;
  overflow-y: hidden;
}
body {
  position: relative;
}
h1 {
  font-family: Lato;
  font-size: 24px;
  font-style: normal;
  font-variant: normal;
  font-weight: 700;
  line-height: 26.4px;
}
h3 {
  font-family: Lato;
  font-size: 14px;
  font-style: normal;
  font-variant: normal;
  font-weight: 700;
  line-height: 15.4px;
}
p {
  font-family: Lato;
  font-size: 14px;
  font-style: normal;
  font-variant: normal;
  font-weight: 400;
  line-height: 20px;
}
blockquote {
  font-family: Lato;
  font-size: 21px;
  font-style: normal;
  font-variant: normal;
  font-weight: 400;
  line-height: 30px;
}
pre {
  font-family: Lato;
  font-size: 13px;
  font-style: normal;
  font-variant: normal;
  font-weight: 400;
  line-height: 18.5714px;
}
@media only screen and (max-width: 1070px) {
  #app{
    flex-direction: column !important;
  }
}
</style>
