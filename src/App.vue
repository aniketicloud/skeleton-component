<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <!-- <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        /> -->
        <h1 class="grey--text">Logo</h1>

        

        <!-- <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        /> -->
      </div>

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <index-skeleton></index-skeleton>
    </v-main>
  </v-app>
</template>

<script>
import IndexSkeleton from "./components/Skeleton/Farm/Web/IndexSkeleton";

export default {
  name: "App",

  components: {
    IndexSkeleton,
  },
};
</script>
