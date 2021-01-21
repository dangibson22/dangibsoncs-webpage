<template>
    <v-container>
        <v-container style="height: 100px;"></v-container>
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
    </v-container>
</template>

<script>
    export default {
        name: "Portfolio"
    }
</script>

<style scoped>

</style>