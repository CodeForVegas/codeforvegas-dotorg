<template>
  <body>
      <NavBar />
      <WelcomeToCFV />
      <AboutUs />
  </body>
</template>

<script>
import NavBar from "../components/nav-bar.vue"
import WelcomeToCFV from "../components/welcome-to-cfv.vue"
import AboutUs from "../components/about-us.vue"

export default {
  name: 'HomePage',
  components: {
    NavBar,
    WelcomeToCFV,
    AboutUs,
  }
}
</script>

<style>

body {
  background: black;
}

</style>
