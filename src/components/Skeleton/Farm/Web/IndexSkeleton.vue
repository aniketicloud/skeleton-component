<template>
  <v-row no-gutters>
    <v-col>
      <skeleton-sheet></skeleton-sheet>
    </v-col>
    <v-col>
      <skeleton-sheet></skeleton-sheet>
    </v-col>
    <v-col>
      <skeleton-sheet></skeleton-sheet>
    </v-col>
  </v-row>
</template>

<script>
import SkeletonSheet from "./SkeletonSheet";
export default {
  components: {
    SkeletonSheet,
  },
};
</script>
