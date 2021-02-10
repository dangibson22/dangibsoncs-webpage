<template>
  <v-container>
    <v-container style="height: 100px;"></v-container>

        <v-container fluid>
          <v-row no-gutters>
            <v-col cols="0" md="2">
              <v-img
                style="border-radius: 4px 0px 0px 4px;"
                src="./../assets/photo-dan.jpg"
              ></v-img>
            </v-col>
            <v-col cols="12" md="10">
              <v-card style="border-radius: 0px 4px 4px 0px; height: 100%;">
                <v-card-title>Background</v-card-title>
                <v-card-text>
                  <div>from St. Louis, MO</div>
                  <div>graduated from University City Senior High in May 2018</div><br>
                  <div>
                    <v-btn dark outlined color="#D32F2F" download :href="`${publicPath}daniel-gibson-resume.pdf`">Download Resume</v-btn>
                  </div>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row><br>
          <v-row no-gutters>
            <v-col cols="12" md="9">
              <v-card style="border-radius: 4px 0px 0px 4px; height: 100%;">
                <v-card-title>Education</v-card-title>
                <v-card-text>
                  <div>expected graduation in May 2022 from Taylor University</div>
                  <div>degree: Bachelor of Science in Computer Science, with Minor in Mathematics</div>
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="0" md="3">
              <v-img
                style="border-radius: 0px 4px 4px 0px; height: 100%;"
                src="https://upload.wikimedia.org/wikipedia/commons/0/02/Euler_Science_Complex_-_Taylor_University_-_Oct_2012.jpg"
              ></v-img>
            </v-col>
          </v-row><br>
          <v-row no-gutters>
            <v-col cols="0" md="3">
              <v-img
                style="border-radius: 4px 0px 0px 4px; height: 100%;"
                src="./../assets/photo-robotics.jpg"
              ></v-img>
            </v-col>
            <v-col cols="12" md="9">
              <v-card style="border-radius: 0px 4px 4px 0px; height: 100%;">
                <v-card-title>Experience</v-card-title>
                <v-card-text>
                  <div style="font-weight: bold;">Job Experience</div>
                  <div>Personnel Assistant at Taylor University</div>
                  <div>Teaching Assistant at Taylor University</div>
                  <div>Order Fulfillment Associate at Home Depot</div>
                  <div>Data Entry Intern at the Law Office of Tracy A. Brown</div>
                  <div style="font-weight: bold;">Programming/Development Experience</div>
                  <div>Four years participating in the First Robotics Competition, including one year as Co-Captain and two years as Head Programmer</div>
                  <div>Worked on many different class projects, including:</div>
                  <div>a checkers game and AI in Python</div>
                  <div>a Battleships AI that adopts to the opponent's strategy in C++</div>
                  <div>a full stack web application in Vue.js</div>
                  <div>a data analysis and visualization report using Observable</div>
                  <div>a pathfinding program using A-star search in Java</div>
                  <div>a comprehensive design and analysis for a Bible Memorization website, including Business Proposal and Systems Requirement Specification documents</div>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row><br>
          <v-row no-gutters>
            <v-col cols="12" md="9">
              <v-card style="border-radius: 4px 0px 0px 4px; height: 100%;">
                <v-card-title>Skills and Languages</v-card-title>
                <v-card-text>
                  <div><span style="font-weight: bold;">Languages Include:</span> Python, Java, C, C++, HTML, CSS, JavaScript, Vue.js, SQL</div>
                  <div><span style="font-weight: bold;">Leadership Experiences:</span> Personnel Assistant at Taylor University, Discipleship Assistant at Taylor University, Co-Captain, Head Programmer and Head Electrician on robotics team</div>
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="0" md="3">
              <v-img
                style="border-radius: 0px 4px 4px 0px; height: 100%;"
                src="https://www.ctrl.blog/media/hero/css-code-block-explosion.jpeg"
              ></v-img>
            </v-col>
          </v-row>
        </v-container>

  </v-container>
</template>

<script>
  export default {
    name: "About",
    data() {
        return {
            publicPath: process.env.BASE_URL,
        }
    }
  }
</script>

<style scoped>

</style>