<template>
  <v-container>
    <v-row >
      <v-col cols="12" sm="6" md="4">
        <skeleton-sheet></skeleton-sheet>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <skeleton-sheet></skeleton-sheet>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <skeleton-sheet></skeleton-sheet>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import SkeletonSheet from "./SkeletonSheet";
export default {
  components: {
    SkeletonSheet,
  },
};
</script>
