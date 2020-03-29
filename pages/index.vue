<template>
  <v-layout column justify-center align-center>
    <v-flex>
      <v-parallax
        src="https://reformedforum.org/wp-content/blogs.dir/1/files/2015/02/book_pile.jpg"
        gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
        dark
      >
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-1 font-weight-thin mb-4">
              COVID19 Student Resources
            </h1>
            <h4 class="subheading">Select the age group of your student</h4>
          </v-col>
        </v-row>
      </v-parallax>
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
.v-stepper_step_step {
  min-width: 90px;
  height: 50px;
}
</style>
