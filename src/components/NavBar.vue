<template>
    <!--
    <v-app-bar
            color="#D32F2F"
            fixed
    >

        <template>
            <v-tabs dark fixed-tabs>
                <v-tab v-bind:to="{name: 'home-page' }">Welcome <v-spacer/><v-icon>mdi-home</v-icon> </v-tab>
                <v-tab v-bind:to="{name: 'about' }" >About Me <v-spacer/><v-icon>mdi-account</v-icon></v-tab>
                <v-tab v-bind:to="{name: 'portfolio' }">My Portfolio <v-spacer/><v-icon>mdi-clipboard-text-multiple</v-icon></v-tab>
                <v-tab v-bind:to="{name: 'contact' }">Contact Info <v-spacer/><v-icon>mdi-email</v-icon></v-tab>
            </v-tabs>
        </template>

    </v-app-bar>
    -->
    <v-container fluid>
        <v-app-bar
            color="#D32F2F"
            fixed
            dark
        >
            <v-btn :to="{ name: 'home-page' }" exact color="#d32f2f">
                <v-toolbar-title>
                    <span class="headline">Daniel Gibson</span>
                </v-toolbar-title>
            </v-btn>
            <v-spacer />
            <v-btn
                style="height: 100%;"
                tile
                depressed
                color="#D32F2F"
                :to="{ name: 'about' }"
                exact
            >
                <v-icon left>mdi-account</v-icon>
                About Me
            </v-btn>
            <v-divider vertical />
            <v-btn
                style="height: 100%;"
                color="#D32F2F"
                tile
                dark
                depressed
                :to="{ name: 'portfolio' }"
                exact
            >
                <v-icon left>mdi-clipboard-text</v-icon>
                My Portfolio
            </v-btn>
            <v-divider vertical />
            <v-btn
                style="height: 100%;"
                color="#D32F2F"
                tile
                dark
                depressed
                :to="{ name: 'contact' }"
                exact
            >
                <v-icon left>mdi-email</v-icon>
                Contact Info
            </v-btn>
        </v-app-bar>
    </v-container>
</template>

<script>
    export default {
        name: "NavBar"
    }
</script>

<style scoped>
    /deep/ .v-toolbar__content {
        padding-top: 0px !important;
        padding-bottom: 0px !important;
    }
</style>