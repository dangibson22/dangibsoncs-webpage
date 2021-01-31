<template>
    <v-container fluid class="pa-0">
        <v-container style="height: 64px;"></v-container>
        <v-parallax dark src="https://www.ctrl.blog/media/hero/css-code-block-explosion.jpeg">
            <v-row class="my-auto" align="center" justify="center">
                <v-col color="white" class="text-center" cols="12">
                    <span class="display-4 font-weight-medium">PORTFOLIO & PROJECTS</span>
                </v-col>
            </v-row>
        </v-parallax>
        <v-sheet class="pa-4">
            <v-row justify="center">
                <v-col cols="12" class="text-center">
                    <span class="display-3">External Links</span>
                </v-col>
            </v-row>
            <v-row justify="center">
                <v-col cols="3"></v-col>
                <v-col cols="3">
                    <v-card>
                        <v-card-title class="justify-center">GitHub</v-card-title>
                        <v-card-text>
                            GitHub is a popular repository-based code sharing hub.
                            Many examples of projects I've worked on are available on this site.
                            Click the link below to learn more!
                        </v-card-text>
                        <v-card-actions>
                            <v-btn color="#D32F2F" style="width: 100%;" outlined href="https://github.com/dangibson22" target="_blank">
                                <v-icon left>mdi-github</v-icon>
                                GitHub
                            </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
                <v-col cols="3">
                    <v-card>
                        <v-card-title class="justify-center">Observable</v-card-title>
                        <v-card-text>
                            Observable is a notebook style platform that implements JavaScript and is useful for creating data visualizations using certain packages.
                            I have used this platform in the past to create visualizations, and my work is available on my profile.
                            Click the link below to learn more!
                        </v-card-text>
                        <v-card-actions>
                            <v-btn color="#D32F2F" outlined style="width: 100%;" href="https://observablehq.com/@dangibson22" target="_blank">
                                <v-icon left>mdi-chart-box-outline</v-icon>
                                Observable
                            </v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
                <v-col cols="3"></v-col>
            </v-row>
        </v-sheet>

        <v-parallax dark class="pt-2 px-0" src="https://mytechdecisions.com/wp-content/uploads/2019/10/AdobeStock_256229414.jpg">
            <span class="text-center display-2">Web Design Projects</span>
            <v-carousel class="px-0 mx-0">
                <v-carousel-item>
                    <v-container fluid>
                        <v-row>
                            <v-col cols="3">
                                <v-card light>
                                    <v-card-title>Corpus Christi</v-card-title>
                                    <v-card-text>
                                        Corpus Christi is a church management software developed by the Missions Computing team at Taylor University.
                                        This is a church management software designed for a church in Ecuador.
                                        With a fully localized language scheme, this application allows for creation of groups, courses and events.
                                        I contributed to this project during January of 2021.
                                    </v-card-text>
                                    <v-divider class="mx-2"/>
                                    <v-card-actions>
                                        <v-btn color="#D32F2F" outlined href="https://github.com/corpus-christi/corpus-christi" target="_blank" block>View More</v-btn>
                                    </v-card-actions>
                                </v-card>
                            </v-col>
                            <v-col cols="3">
                                <v-card light>
                                    <v-card-title>Taylor Rideshare</v-card-title>
                                    <v-card-text>
                                        This was a final project for the Multi Tier Web Application Development class at Taylor University.
                                        The app allows users to find drivers and cars going to certain locations, and also allows users to sign up as a driver.
                                        I developed this project in Fall of 2019.
                                    </v-card-text>
                                    <v-divider class="mx-2"/>
                                    <v-card-actions>
                                        <v-btn href="https://github.com/dangibson22/rideshare-project" target="_blank" block outlined color="#D32F2F">View More</v-btn>
                                    </v-card-actions>
                                </v-card>
                            </v-col>
                            <v-col cols="3">
                                <v-card light>
                                    <v-card-title>Personal Portfolio Website</v-card-title>
                                    <v-card-text>
                                        This is a project I built and deployed myself.
                                        It is a website designed to show off my experience as well as past projects I've worked on to employers and anyone else who wants to visit.
                                        (Fun fact - you're currently looking at this project!)
                                    </v-card-text>
                                    <v-divider class="mx-2"/>
                                    <v-card-actions>
                                        <v-btn href="https://github.com/dangibson22/dangibsoncs-webpage" target="_blank" block outlined color="#D32F2F">View More</v-btn>
                                    </v-card-actions>
                                </v-card>
                            </v-col>
                        </v-row>
                    </v-container>
                </v-carousel-item>
            </v-carousel>

        </v-parallax>
        <!--
        <v-card>
            <v-card-title>External Links</v-card-title>
            <v-container fluid>
                <v-row>
                    <v-col sm="6">
                        <v-card>
                            <v-hover v-slot="{ hover }">
                                <v-card :elevation="hover ? 6 : 0" height="300px" width="600px">
                                    <a href="https://github.com/dangibson22" target="_blank">
                                        <v-img height="300px" width="600px"
                                            src="https://pixy.org/src2/576/thumbs350/5762188.jpg">
                                        </v-img>
                                    </a>
                                </v-card>
                            </v-hover>
                            <v-card-title>GitHub</v-card-title>
                            <v-card-text>View my GitHub page to see my projects!</v-card-text>
                        </v-card>
                    </v-col>
                    <v-col sm="6">
                        <v-card>
                            <v-hover v-slot="{ hover }">
                                <v-card :elevation="hover ? 6 : 0" height="300px" width="600px">
                                    <a href="https://observablehq.com/@dangibson22" target="_blank">
                                        <v-img height="300px" width="600px"
                                                src="https://discoversociety.org/wp-content/uploads/2020/12/area-line-charts-md.jpg">
                                        </v-img>
                                    </a>
                                </v-card>
                            </v-hover>
                            <v-card-title>ObservableHQ</v-card-title>
                            <v-card-text>View my ObservableHQ page to see my data visualization projects!</v-card-text>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </v-card>
        <br>
        <v-card>
            <v-card-title>Web Design Projects</v-card-title>
            <v-container fluid>
                <v-row>
                    <v-col sm="3">
                        <v-card height="450" outlined>
                            <v-card-title>Corpus Christi</v-card-title>
                            <v-card-subtitle>Localized church management software</v-card-subtitle>
                            <v-divider class="mx-4"></v-divider>
                            <v-card-text>
                                Corpus Christi is a church management software developed by the Missions Computing team at Taylor University. This is a church management software designed for a church in Ecuador. With a fully localized language scheme, this application allows for creation of groups, courses and events. I contributed to this project during January of 2020.
                            </v-card-text>
                            <v-spacer/>
                            <v-card-actions>
                                    <v-btn href="https://github.com/corpus-christi/corpus-christi" target="_blank" block outlined color="red">View More</v-btn>
                            </v-card-actions>
                        </v-card>
                    </v-col>
                    <v-col sm="3">
                        <v-card max-height="500">
                            <v-card-title>Taylor Rideshare</v-card-title>
                            <v-card-subtitle>Carpooling software for university students</v-card-subtitle>
                            <v-divider class="mx-4"></v-divider>
                            <v-card-text>
                                This was a final project for the Multi Tier Web Application Development class at Taylor University. The app allows users to find drivers and cars going to certain locations, and also allows users to sign up as a driver.
                            </v-card-text>
                            <v-card-actions>
                                <v-btn href="https://github.com/dangibson22/rideshare-project" target="_blank" block outlined color="red">View More</v-btn>
                            </v-card-actions>
                        </v-card>
                    </v-col>
                    <v-col sm="3">
                        <v-card>
                            <v-card-title>More to come soon!</v-card-title>
                            <v-card-text>This section of the website is still under development. Come back soon to see more projects!</v-card-text>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </v-card>
        -->
    </v-container>
</template>

<script>
    export default {
        name: "Portfolio"
    }
</script>

<style scoped>

</style>