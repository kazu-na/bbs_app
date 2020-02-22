<template>
  <v-div id="app">
    <Header/>
    <h1>This is BBS_APP</h1>
    <p>{{ message }}</p>
    <Top/>
  </v-div>
</template>

<script>
import Header from "./components/Header";
import Top from "./components/Top";

export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  },
  components: {
    Header,
    Top,
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
