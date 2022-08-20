<template>
    <div>
        <b-navbar class="navbar" type="dark">
        <b-navbar-brand href="/">
          <b-img class="logo" :src="logo"></b-img>     
        </b-navbar-brand>
        <b-navbar-nav class="nav-links">
          <b-nav-item class="nav-link" href="#about-us">About Us</b-nav-item>
          <b-nav-item class="nav-link" href="#projects">Projects</b-nav-item>
          <b-nav-item class="nav-link" href="#get-involved">Get Involved</b-nav-item>
        </b-navbar-nav>
      </b-navbar>
    </div>
</template>

<script>
export default {
    data() {
        return {
      logo: require("../assets/CFV-logo.png")
        }
    }
}
</script>

<style>

.logo {
  height: 7rem;
  width: 7rem;
}

.navbar {
    justify-content: space-between;
    align-items: center;
}

.navbar .nav-links .nav-link {
    color: white;
    font-family: 'Roboto Mono';
}

</style>