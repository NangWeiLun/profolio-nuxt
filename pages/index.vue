<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <Welcome />
      <br />
      <Education />
      <br />
      <Project />
      <br />
      <Career />
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'
import Welcome from '~/components/Welcome.vue'
import Education from '~/components/Education.vue'
import Project from '~/components/Project.vue'
import Career from '~/components/Career.vue'

export default {
  components: {
    Logo,
    VuetifyLogo,
    Welcome,
    Education,
    Project,
    Career,
  },
}
</script>
