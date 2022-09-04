<template>
  <v-container>
    <v-row justify="center" align="center">
      <v-col cols="8" sm="12" md="10">
        <List />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import List from "@/components/List.vue";

export default {
  components: {List,}
}
</script>
