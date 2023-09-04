<script>
import NavBar from "../components/NavBar.vue"
import Hero from "../components/Hero.vue"
export default {
  components: {
    NavBar,
    Hero
  }
}
</script>

<template>
  <div class="header-container">
    <NavBar />
    <Hero />
  </div>
</template>

<style scoped lang="scss">
.header-container {
  height: 1080px;
  background-image: url(../assets/images/index-banner-bg.png);
  background-size: cover;
  background-color: black;
  background-repeat: no-repeat;
  position: relative;
  overflow: hidden;
  position: relative;

}


</style>
