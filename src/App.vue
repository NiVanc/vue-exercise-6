<template>
  <div class="container">
    <app-header></app-header>
    <hr />
    <div class="row">
      <app-servers></app-servers>
      <app-server-details></app-server-details>
    </div>
    <hr />
    <app-footer></app-footer>
  </div>
</template>

<script>
import Servers from "./Server/Servers.vue";
import Header from "./Shared/Header.vue";
import Footer from "./Shared/Footer.vue";
import ServerDetails from "./Server/ServerDetails.vue";

export default {
  components: {
    "app-header": Header,
    "app-footer": Footer,
    "app-server-details": ServerDetails,
    "app-servers": Servers
  }
};
</script>

<style>
</style>
