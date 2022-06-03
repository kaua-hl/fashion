<template>
  <Hero />
  <Features />
  <Categories />
  <Popular />
</template>

<script lang="ts">
import Features from "@/components/Home/Features/Features.vue";
import Hero from "@/components/Home/Hero/Hero.vue";
import Categories from "@/components/Home/Categories/Categories.vue";
import Popular from "@/components/Home/Popular/Popular.vue";

export default {
  components: { Features, Hero, Categories, Popular },
};
</script>

<style></style>
