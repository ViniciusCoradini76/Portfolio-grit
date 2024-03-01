<template>
  <Navbar />
  <router-view />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue"
import Footer from "./components/Footer.vue"

export default {
  name: "App",
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
}

.container {
  display: grid;
  grid-auto-flow: column;
  grid-auto-columns: 1fr;
}
</style>
