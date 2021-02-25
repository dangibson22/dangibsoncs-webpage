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
            <v-container fluid>
            <v-row justify="center">
                <v-col cols="12" class="text-center">
                    <span class="display-3">External Links</span>
                </v-col>
            </v-row>
            <v-row justify="center">
                <v-col cols="0" sm="12"></v-col>
                <v-col cols="12" sm="3">
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
                <v-col cols="12" sm="3">
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
                <v-col cols="0" sm="12"></v-col>
            </v-row>
            </v-container>
        </v-sheet>

        <v-sheet class="pt-2 px-0" color="#ebebeb">
            <v-container fluid>
            <v-row justify="center">
                <v-col cols="12" class="text-center">
                    <span class="display-3">Web Design Projects</span>
                </v-col>
            </v-row>
            <v-row>
                <v-col cols="12" sm="3">
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
                <v-col cols="12" sm="3">
                    <v-card light>
                        <v-card-title>Dwell Memorization App</v-card-title>
                        <v-card-text>
                            Dwell is a web application developed by my team in the Information Systems Analysis class.
                            The app is designed as a Scripture Memorization Program, but is designed in a way that it
                            could be adapted to any other memorization content.
                            We created a full design for the application, including designs for a front-end UI/UX, as well as
                            a back-end database with lots of flexibility to add/adapt new features to the application.
                        </v-card-text>
                        <v-divider class="mx-2"/>
                        <v-card-actions>
                            <v-btn color="#D32F2F" download :href="`${publicPath}dwell-business-proposal.pdf`" outlined block>Download Business Proposal</v-btn>
                        </v-card-actions>
                        <v-card-actions>
                            <v-btn color="#D32F2F" download :href="`${publicPath}dwell-system-requirements-specification.pdf`" outlined block>Download SRS</v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="3">
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
                <v-col cols="12" sm="3">
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
        </v-sheet>
        <v-sheet>
            <v-container fluid>
            <v-row justify="center">
                <v-col cols="12" class="text-center">
                    <span class="display-3">Data Structures & Algorithms Projects</span>
                </v-col>
            </v-row>
            <v-row>
                <v-spacer/>
                <v-col cols="12" sm="3">
                    <v-card light>
                        <v-card-title>Prime Partitions Project</v-card-title>
                        <v-card-text>
                            This was a project for my Language Structures class.
                            The goal of this project was to take a given algorithm in Python and recreate it in six different languages.
                            I worked in Ada, Prolog and Scheme, while my partner worked in Haskell, JavaScript and C#.
                            It was very interesting to learn some very different languages and look at different ways to interact with computers.
                            This project was done in the Spring of 2021.
                        </v-card-text>
                        <v-divider class="mx-2"/>
                        <v-card-actions>
                            <v-btn href="https://github.com/dangibson22/COS382-A00" target="_blank" block outlined color="#D32F2F">View More</v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="3">
                    <v-card light>
                        <v-card-title>Pathfinding Algorithm Project</v-card-title>
                        <v-card-text>
                            This was a project for my Data Structures & Algorithms class.
                            The goal of this project was to develop a pathfinding algorithm in Java using A* search.
                            We also implemented a heuristic cost to cause the path to always move closer to the destination.
                            Another element of this project is the walker class, which traverses the path at a speed in proportion to the cost.
                            This project was done in Fall of 2019.
                        </v-card-text>
                        <v-divider class="mx-2"/>
                        <v-card-actions>
                            <v-btn href="https://github.com/dangibson22/COS265-P04-pathfinding" target="_blank" block outlined color="#D32F2F">View More</v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="3">
                    <v-card light>
                        <v-card-title>KD Tree Project</v-card-title>
                        <v-card-text>
                            This was also a project for my Data Structures & Algorithms class.
                            The goal of this project was to use a K-D tree to organize a k-dimensional set of data.
                            We used the K-D tree structure, based upon a binary tree, to implement an efficient searching
                            and organization of this data.
                            The project also includes several ways to visualize the usage of this data structure, using
                            sets of 2D points and showing the nearest and nearest k points.
                            This project was done in Fall 2019.
                        </v-card-text>
                        <v-divider class="mx-2"/>
                        <v-card-actions>
                            <v-btn href="https://github.com/dangibson22/P05-KDTrees" target="_blank" block outlined color="#D32F2F">View More</v-btn>
                        </v-card-actions>
                    </v-card>
                </v-col>
                <v-spacer/>
            </v-row>
            </v-container>
        </v-sheet>
    </v-container>
</template>

<script>
    export default {
        name: "Portfolio",
        data() {
            return {
                publicPath: process.env.BASE_URL,
            }
        }
    }
</script>

<style scoped>

</style>