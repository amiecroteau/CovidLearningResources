<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-center"></div>
      <v-card light>
        <v-card-title class="headline">
          Unique Learning Resources
        </v-card-title>
        <v-card-text>
          <Stepper />
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire">
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Stepper from "../components/Stepper.vue";
export default {
  data: {
    age: null
  },

  components: {
    Stepper
  }
};
</script>
