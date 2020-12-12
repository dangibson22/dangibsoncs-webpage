<template>
  <v-container fluid>
    <v-app-bar
            color="#424242"
            fixed
            src="https://upload.wikimedia.org/wikipedia/commons/d/de/St_Louis_night_expblend.jpg"
            fade-img-on-scroll
            shrink-on-scroll
            hide-on-scroll
            height="725px"
            min-height="56px"
    >
      <v-spacer />
      <v-toolbar-title style="color: white; font-size: 48px">
        Daniel Gibson
      </v-toolbar-title>
      <v-spacer />

    </v-app-bar>
    <v-container style="min-height: 1000px;"></v-container>

    <v-card>
      <v-container fluid>
        <v-row>
          <v-col cols="12" sm="12" md="6" lg="6">
            <v-card style="height: 100%;" ><v-card-title class="display-1" ><br/><br/>Hello, my name is <br>Daniel Gibson!</v-card-title></v-card>
          </v-col>
          <v-col cols="12" sm="6" md="3" lg="3">
            <v-card>
            <v-img
              src="https://scontent-ort2-1.xx.fbcdn.net/v/t31.0-8/21641139_2002480773304504_6051448858350316672_o.jpg?_nc_cat=107&ccb=2&_nc_sid=09cbfe&_nc_ohc=WmcCLc_stIcAX9P_jlM&_nc_ht=scontent-ort2-1.xx&oh=ac725e28871c34d1ff6de394ee9dc13d&oe=5FF8A06E"
            />
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="3" lg="3">
            <v-card>
            <v-img
              src="https://scontent-ort2-1.xx.fbcdn.net/v/t1.0-9/48339943_2277960122423233_4504219842122874880_o.jpg?_nc_cat=101&ccb=2&_nc_sid=730e14&_nc_ohc=sYaTjkDXK9AAX_MuRRi&_nc_ht=scontent-ort2-1.xx&oh=c2e2f1a3ed41296040229d3e408c43a0&oe=5FF5A2D1"
            />
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12">
            <v-card><v-card-subtitle>I'm a junior at Taylor University looking to graduate with a BS of Computer Science and a Minor in Mathematics. I have experience in a wide array of Computer Science disciplines, including web design, data structures and algorithms and data analysis and visualization.</v-card-subtitle></v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" md="4" lg="4">
            <v-hover v-slot="{ hover }">
              <v-card>
                <v-img
                        :aspect-ratio="16/9"
                        src="https://static.thenounproject.com/png/732580-200.png"
                >
                  <v-expand-transition>
                    <v-btn
                            v-if="hover"
                            v-bind:to="{name: 'about' }"
                            class="d-flex transition-fast-in-fast-out darken-2 v-card--reveal display-1 white"
                            style="height: 100%; opacity: 50%; width: 100%;"
                    >
                      More about me
                    </v-btn>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="12" md="4" lg="4">
            <v-hover v-slot="{ hover }">
              <v-card>
                <v-img
                        :aspect-ratio="16/9"
                        src="https://cdn.stocksnap.io/img-thumbs/960w/computer-code_AWXC4NOFZN.jpg"
                >
                  <v-expand-transition>
                    <v-btn
                            v-if="hover"
                            v-bind:to="{name: 'portfolio' }"
                            class="d-flex transition-fast-in-fast-out darken-2 v-card--reveal display-1 white"
                            style="height: 100%; opacity: 50%; width: 100%;"
                    >
                      View projects
                    </v-btn>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="12" md="4" lg="4">
            <v-hover v-slot="{ hover }">
              <v-card>
                <v-img
                        :aspect-ratio="16/9"
                        src="https://cdn.pixabay.com/photo/2016/12/15/12/24/contact-us-1908762_1280.png"
                >
                  <v-expand-transition>
                    <v-btn
                            v-if="hover"
                            v-bind:to="{name: 'contact' }"
                            class="d-flex transition-fast-in-fast-out darken-2 v-card--reveal display-1 white"
                            style="height: 100%; opacity: 50%; width: 100%;"
                    >
                      Get in contact
                    </v-btn>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
      </v-container>
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