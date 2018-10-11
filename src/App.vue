<template>
  <div class="container">
    <header></header>
    <hr>
    <div class="row">
      <servers></servers>
      <server-details></server-details>
    </div>
    <hr>
    <footer></footer>
  </div>
</template>

<script>
import Header from "./components/Shared/Header.vue"
import Footer from "./components/Shared/Footer.vue"
import Servers from "./components/Server/Servers.vue"
import ServerDetails from "./components/Server/ServerDetails.vue"

export default {
  components: {
    Header,
    Footer,
    Servers,
    ServerDetails
  }
}
</script>

<style></style>
