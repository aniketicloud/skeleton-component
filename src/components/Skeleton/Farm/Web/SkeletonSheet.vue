<template>
  <div>
    <!-- Mobile view -->
    <div v-if="dataAcquired">
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
    </div>
    <!-- Error Component of Mobile -->
    <div v-else>
      <error-component></error-component>
    </div>

    <!-- Desktop View -->
    <div v-if="dataAcquired">
      <v-sheet height="566" class="d-none d-sm-flex mx-4">
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
    <!-- Error Component of Desktop -->
    <div v-else>
      <error-component></error-component>
    </div>
  </div>
</template>

<script>
import TextSkeleton from "./TextSkeleton";
import HeadingSkeleton from "./HeadingSkeleton";
import ErrorComponent from "./ErrorComponent";
import { mapState } from "vuex";
export default {
  components: {
    TextSkeleton,
    HeadingSkeleton,
    ErrorComponent,
  },
  computed:{
    ...mapState(["dataFetching", "dataAcquired"])
  }
};
</script>
