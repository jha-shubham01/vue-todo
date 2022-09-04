<template>
  <v-row>
    <v-col cols="8" md="8" sm="12">
      <h2 >All Tasks</h2>
    </v-col>
    <v-col cols="3" md="3" sm="10">
      <v-text-field label="Search Tasks" append-icon="mdi-magnify">
      </v-text-field>
    </v-col>
    <v-col cols="1" md="1" sm="1" class="text-center">
      <v-btn
        fab
        small
        dark
        color="grey darken-1"
      >
        <v-icon dark>
          mdi-plus
        </v-icon>
      </v-btn>
    </v-col>
  </v-row>
</template>
