<template>
  <div class="profilePic" alt="Personal picture"/>
</template>

<script>
export default {
  name: "ProfilePic"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.profilePic{
  height: 50rem;
  width: 50rem;
  border-radius: 50%;
  background-image: url("../assets/pic.png");
  background-position: center;
  background-size: 155%;
}
</style>
