<template>
  <div>
    <v-sheet
      width="404"
      height="566"
      tile
      class="mb-8 hidden-sm-and-down"
    >
      <header-skeleton></header-skeleton>
      <text-skeleton></text-skeleton>
      <text-skeleton></text-skeleton>
      <text-skeleton></text-skeleton>
      <text-skeleton></text-skeleton>
    </v-sheet>

    <v-sheet
      width="404"
      height="316"
      tile
      class="mb-8 hidden-sm-and-down"
    >
      <header-skeleton></header-skeleton>
      <text-skeleton></text-skeleton>
      <text-skeleton></text-skeleton>
    </v-sheet>
  </div>
</template>

<script>
import TextSkeleton from "./TextSkeleton";
import HeaderSkeleton from "./HeaderSkeleton";
export default {
  components: {
    TextSkeleton,
    HeaderSkeleton,
  },
};
</script>
