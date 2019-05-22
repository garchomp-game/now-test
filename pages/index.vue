<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-btn to="hoge/about">about page</v-btn>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
