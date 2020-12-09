<template>
  <v-container>
    <v-app-bar
            color="#424242"
            fixed
            src="https://arc-anglerfish-arc2-prod-tronc.s3.amazonaws.com/public/ILT2STMS45BTDBAHGCXUK3C63I.jpg"
            fade-img-on-scroll
            shrink-on-scroll
            hide-on-scroll
            height="725px"
            min-height="56px"
    >
      <v-spacer />
      <v-toolbar-title style="color: white; font-size: 72px">
        Daniel Gibson
      </v-toolbar-title>
      <v-spacer />

    </v-app-bar>
    <v-container style="height: 1500px;"></v-container>
    <v-card>
      <v-row>
        <v-col>
          <v-card-title class="headline">
            Hello!
          </v-card-title>
          <v-card-subtitle>
            My name is Daniel Gibson! I'm a junior at Taylor University, aiming to graduate with a BS in Computer Science and a Minor in Mathematics.
          </v-card-subtitle>
          </v-col>
        <v-col>
          <v-img src="https://scontent-ort2-1.xx.fbcdn.net/v/t31.0-8/21641139_2002480773304504_6051448858350316672_o.jpg?_nc_cat=107&ccb=2&_nc_sid=09cbfe&_nc_ohc=WmcCLc_stIcAX9P_jlM&_nc_ht=scontent-ort2-1.xx&oh=ac725e28871c34d1ff6de394ee9dc13d&oe=5FF8A06E"
                 max-height="250"
                 max-width="250"
          >
          </v-img>
        </v-col>
      </v-row>

    </v-card>
  </v-container>
</template>

<script>
  export default {
    name: "Home.vue"
  }
</script>

<style scoped>

</style>