<template>
  <v-app>
    <VuetifyComponent
    :intro="intro"
    />
  </v-app>
</template>

<script>
import VuetifyComponent from './components/VuetifyComponent'

export default {
  name: 'App',
  components: {
    VuetifyComponent
  },
  data(){
    return {
      intro: {
        title: "Welcome to my Vuetify Playground!",
        purpose: "The purpose of this is to develop responsive, reusable, and custmoizable components."
      }
    }
  }
}
</script>

<style>

</style>
