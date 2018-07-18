<template>
  <v-container>
  <h1>{{Intro.title}}</h1>
  <p>{{Intro.purpose}}</p>
  </v-container>
</template>

<script>
export default {
  name: 'VuetifyComponent',
  props: ["Intro"]
}
</script>

<style scoped>

</style>
