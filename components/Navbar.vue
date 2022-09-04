<template>
  <div>
    <v-app-bar dense>
      <v-toolbar-title>
        TODO
      <v-icon>mdi-text</v-icon>
      </v-toolbar-title>

      <v-spacer></v-spacer>
      <v-btn icon>
        <v-icon>mdi-format-list-checkbox</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-playlist-check</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-playlist-remove</v-icon>
      </v-btn>
      
      <v-btn icon>
        <v-icon>mdi-playlist-plus</v-icon>
      </v-btn>
      <v-avatar color="green darken-5" size="30">
        <v-icon dark>
          mdi-account
        </v-icon>
      </v-avatar>
    </v-app-bar>
  </div>
</template>