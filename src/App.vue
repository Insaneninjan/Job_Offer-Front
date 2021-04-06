<template>
    <v-app>
        <v-app-bar color="success" dark app>
            <v-toolbar-title>Job Offer</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items>
                <v-btn text to="/">Home</v-btn>
                <v-btn text to="/editor">Add job</v-btn>
            </v-toolbar-items>
        </v-app-bar>
        <v-content>
            <router-view />
        </v-content>
        <v-footer color="success" dark app class="justify-center">
            Django
        </v-footer>
    </v-app>
</template>

<script>
export default {
};
</script>