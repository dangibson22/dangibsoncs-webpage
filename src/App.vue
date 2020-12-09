<template>
  <v-app style="background-color: #424242">
    <nav-bar />
    <v-content>
      <v-container> <router-view></router-view> </v-container>
    </v-content>
  </v-app>
</template>

<script>
  console.log("loaded");
  import NavBar from "./components/NavBar.vue";

  export default {
    name: "App",
    components: {
      NavBar
    }
  }
</script>

<style scoped>

</style>