<template>
  <div>
    <!-- Mobile view -->
    <v-sheet height="318" class="d-sm-none mx-4">
      <v-row>
        <v-col>
          <heading-skeleton></heading-skeleton>
          <div>
            <text-skeleton></text-skeleton>
            <text-skeleton></text-skeleton>
          </div>
          <div>
            <text-skeleton></text-skeleton>
            <text-skeleton></text-skeleton>
          </div>
        </v-col>
      </v-row>
    </v-sheet>

    <!-- Desktop View -->
    <div>
      <v-sheet height="566" class="d-none d-sm-flex mx-4">
        <v-row dense>
          <v-col>
            <heading-skeleton></heading-skeleton>
            <div class="mb-4">
              <text-skeleton></text-skeleton>
              <text-skeleton></text-skeleton>
            </div>
            <div class="mb-4">
              <text-skeleton></text-skeleton>
              <text-skeleton></text-skeleton>
            </div>
            <div class="mb-4">
              <text-skeleton></text-skeleton>
              <text-skeleton></text-skeleton>
            </div>
            <div class="mb-4">
              <text-skeleton></text-skeleton>
              <text-skeleton></text-skeleton>
            </div>
          </v-col>
        </v-row>
      </v-sheet>

      <v-sheet height="316" class="d-none d-sm-flex mx-4">
        <v-row>
          <v-col>
            <heading-skeleton></heading-skeleton>
            <div class="mb-4">
              <text-skeleton></text-skeleton>
              <text-skeleton></text-skeleton>
            </div>
            <div class="mb-4">
              <text-skeleton></text-skeleton>
              <text-skeleton></text-skeleton>
            </div>
          </v-col>
        </v-row>
      </v-sheet>
    </div>
  </div>
</template>

<script>
import TextSkeleton from "./TextSkeleton";
import HeadingSkeleton from "./HeadingSkeleton";
export default {
  components: {
    TextSkeleton,
    HeadingSkeleton,
  },
};
</script>
