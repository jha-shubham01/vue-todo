<template>
  <v-app dark>
    <NavBar />
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import NavBar from "@/components/Navbar.vue";

export default {
  components: {
    NavBar,
  },
}
</script>
