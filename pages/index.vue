<template>
  <body>
      <NavBar />
      <WelcomeToCFV />
  </body>
</template>

<script>
import NavBar from "../components/nav-bar.vue"
import WelcomeToCFV from "../components/welcome-to-cfv.vue"

export default {
  name: 'HomePage',
  components: {
    NavBar,
    WelcomeToCFV,
  }
}
</script>

<style>

body {
  background: black;
}

</style>
