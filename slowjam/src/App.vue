<template>
 <v-app light>
    <v-toolbar class="white">
      <v-toolbar-title >Slow Jam Society</v-toolbar-title>
    </v-toolbar>
    <router-view/>
  </v-app>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
