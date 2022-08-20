<template>
  <body>
      <NavBar />
      <WelcomeToCfv />
      <AboutUs />
      <ProjectsInfo />
      <EventsInfo />
      <ContactUs />
      <TeamMembers />
      <ExtraInfo />
  </body>
</template>

<script>
import projectsInfo from '~/components/projects-info.vue'

export default {
  name: 'HomePage',
  components: { projectsInfo },
  head: {
    title: 'Code For Vegas',
  }
}
</script>

<style>

body {
  background: black;
}

</style>
