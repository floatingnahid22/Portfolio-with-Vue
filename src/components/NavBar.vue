<template>
  <v-app-bar app color="#cyan" dark flat class="px-8">
    <v-btn href="/" icon>
      <v-img src="logo.png" contain max-height="100"></v-img>
    </v-btn>

    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('skills')">Skills</v-btn>
    <v-btn text @click="scroll('projects')">Projects</v-btn>
    <v-btn text @click="scroll('contact')"> contact</v-btn>
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

<style></style>
