<template>
  <Header />
  <Home />
  <Footer />
</template>

<script lang="ts">
import Header from "./components/Header/Header.vue";
import Home from "./pages/Home/Home.vue";
import Footer from "./components/Footer/Footer.vue";

export default {
  components: { Header, Home, Footer },
};
</script>

<style>
@import "./assets/css/index.css";
</style>
