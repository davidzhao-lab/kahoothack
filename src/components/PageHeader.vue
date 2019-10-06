<template>
  <div class="header">
    <h1 class="display-3 font-weight-black">{{title}}</h1>
    <h2 class="display-1">{{subtitle}}</h2>
    <v-btn outlined class="discord" color="primary">
      <v-icon left @click="redirectDiscord()">link</v-icon>discord
    </v-btn>
  </div>
</template>

<script>
export default {
  name: "PageHeader",
  props: ["title", "subtitle"],
  methods: {
    redirectDiscord() {
      document.location.href = "https://discordapp.com/invite/nJTSkx6";
    }
  }
};
</script>

<style scoped>
.header {
  width: 100%;
  text-align: center;
  padding-top: 7.5vh;
  padding-bottom: 3vh;
}

.discord {
  margin-top: 1vh;
}
</style>

