<template>
  <v-app class="app-container">
    <app-bar></app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import AppBar from "./components/AppBar.vue"
export default Vue.extend({
  name: "App",
  components: { AppBar },
  data: () => ({
    //
  }),
});
</script>
