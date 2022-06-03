<template>
  <Header />
  <Home />
</template>

<script lang="ts">
import Header from "./components/Header/Header.vue";
import Home from "./pages/Home/Home.vue";

export default {
  components: { Header, Home },
};
</script>

<style>
@import "./assets/css/index.css";
</style>
