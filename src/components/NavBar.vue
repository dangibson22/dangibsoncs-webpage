<template>
    <v-app-bar
            color="#D32F2F"
            fixed
    >
        <!--<v-btn style="height: 100%; border-radius: 0px; color: white; opacity: 100%" text v-bind:to="{name: 'home-page' }">
            Daniel Gibson
        </v-btn>-->

        <!--<v-spacer />
        <v-btn style="height: 100%; border-radius: 0px; color: white" text v-bind:to="{name: 'about' }">
            About
        </v-btn>
        <v-btn style="height: 100%; border-radius: 0px; color: white" text v-bind:to="{name: 'portfolio' }">
            Portfolio
        </v-btn>
        <v-btn style="height: 100%; border-radius: 0px; color: white" text v-bind:to="{name: 'contact' }">
            Contact
        </v-btn>-->
        <template>
            <v-tabs dark fixed-tabs>
                <v-tab v-bind:to="{name: 'home-page' }">Welcome <v-spacer/><v-icon>mdi-home</v-icon> </v-tab>
                <v-tab v-bind:to="{name: 'about' }" >About Me <v-spacer/><v-icon>mdi-account</v-icon></v-tab>
                <v-tab v-bind:to="{name: 'portfolio' }">My Portfolio <v-spacer/><v-icon>mdi-clipboard-text-multiple</v-icon></v-tab>
                <v-tab v-bind:to="{name: 'contact' }">Contact Info <v-spacer/><v-icon>mdi-email</v-icon></v-tab>
            </v-tabs>
        </template>

    </v-app-bar>
</template>

<script>
    export default {
        name: "NavBar"
    }
</script>

<style scoped>

</style>