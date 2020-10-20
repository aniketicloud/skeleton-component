<template>
  <v-row>
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
