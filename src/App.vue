<template>
  <v-app style="background-color: #424242">
    <nav-bar class="px-0 mx-0 py-0 my-0" />
    <v-content>
      <v-container fluid class="px-0 mx-0 py-0 my-0"> <router-view></router-view> </v-container>
    </v-content>
    <siteFooter class="py-0" />
  </v-app>
</template>

<script>
  console.log("loaded");
  import NavBar from "./components/NavBar.vue";
  import siteFooter from "./components/Footer.vue";

  export default {
    name: "App",
    components: {
      NavBar,
      siteFooter,
    }
  }
</script>

<style scoped>

</style>