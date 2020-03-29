<template>
  <v-layout column justify-center align-center>
    <v-flex lg12>
      <Stepper />
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

<style scoped>
.app {
  background-color: teal;
}
.contact {
  border-width: 1px;
  border-color: grey;
}
</style>
