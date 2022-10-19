<template>
  <v-app-bar app color="black" dark flat class="px-12">
    <v-btn>
      <v-icon color="yellow" left class="mr-2">fas fa-signature</v-icon>최용태의
      포트폴리오
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')" class="text-yellow">Home</v-btn>
    <v-btn text @click="scroll('about')">about </v-btn>
    <v-btn text @click="scroll('List')">List</v-btn>
    <v-btn text @click="scroll('Trip Photo')">Trip Photo</v-btn>
    <v-btn text @click="scroll('Best Trip')">Best Trip</v-btn>
    <v-btn text @click="scroll('Book')">Book</v-btn>
    <v-btn text @click="scroll('hobbie')">hobbie</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style >
</style>
