<template>
  <v-container fluid class="mx-0 px-0 py-0">

    <!-- 4368x2912 -->
    <v-container style="height: 64px;"></v-container>
    <v-parallax src="./../assets/photo-stl-copy.jpg" height="800">
      <v-container fluid>
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <span class="display-4 font-weight-black">DANIEL GIBSON</span>
          </v-col>
          <v-col class="text-center" cols="12">
            <span class="display-1">Junior at Taylor University</span>
          </v-col>
          <v-col class="text-center">
            <v-btn class="mr-1 ml-1" :to="{ name: 'about' }" color="white" outlined>Learn more about me</v-btn>
            <v-btn class="mr-1 ml-1" :to="{ name: 'portfolio' }" color="white" outlined>View projects</v-btn>
            <v-btn class="mr-1 ml-1" :to="{ name: 'contact' }" color="white" outlined>Get in touch</v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-parallax>

    <v-container fluid class="px-0 py-0">
      <v-sheet>
        <v-row no-gutters>
          <v-col cols="12" sm="4">
              <v-img src="./../assets/photo-dan.jpg"></v-img>
          </v-col>
          <v-col cols="12" sm="8">
              <v-card-title class="display-3">Hello, my name is Daniel Gibson!</v-card-title>
              <v-card-text>
                I'm currently a junior at Taylor University, pursuing a Bachelor of Science degree in Computer Science with a minor in Mathematics.
                This summer, I'm hoping to put my skills to use and I'm looking for internship opportunities!
                I have experience in a wide array of disciplines, including full stack web development, data structures and algorithms, and data analysis and visualization.
                Feel free to browse the site to learn more about me & my experience!
              </v-card-text>
              <v-card-actions>
                <v-container fluid>
                  <v-row class="mx-0">
                    <v-col cols="12" md="4">
                      <v-hover v-slot="{ hover }">
                        <v-card>
                          <v-img
                                  :aspect-ratio="16/9"
                                  src="./../assets/photo-taylor.jpg"
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
                    <v-col cols="12" md="4">
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
                    <v-col cols="12" md="4">
                      <v-hover v-slot="{ hover }">
                        <v-card>
                          <v-img
                                  :aspect-ratio="16/9"
                                  src="https://mk0h360connecth0vd5d.kinstacdn.com/wp-content/uploads/2019/11/hassan-ouajbir-IYU_YmMRm7s-unsplash-1024x683.jpg"
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
                  <v-divider class="mx-4 my-2" />
                  <v-row class="mx-0">
                    <v-col cols="4">
                      <v-btn color="#D32F2F" outlined style="width: 100%;" href="https://github.com/dangibson22" target="_blank">
                        <v-icon left>mdi-github</v-icon>
                        GitHub
                      </v-btn>
                    </v-col>
                    <v-col cols="4">
                      <v-btn color="#D32F2F" outlined style="width: 100%;" href="https://observablehq.com/@dangibson22" target="_blank">
                        <v-icon left>mdi-chart-box-outline</v-icon>
                        Observable
                      </v-btn>
                    </v-col>
                    <v-col cols="4">
                      <v-btn color="#D32f2f" outlined style="width: 100%;" href="https://www.taylor.edu" target="_blank">
                        <v-icon left>mdi-school-outline</v-icon>
                        Taylor University
                      </v-btn>
                    </v-col>
                  </v-row>
                </v-container>
              </v-card-actions>
          </v-col>
        </v-row>
      </v-sheet>
    </v-container>



  </v-container>
</template>

<script>
  export default {
    name: "Home.vue"
  }
</script>

<style scoped>

</style>