<template>
  <Hero />
  <Features />
  <Categories />
  <Popular />
  <Testimonials />
  <Discount />
</template>

<script lang="ts">
import Features from "@/components/Home/Features/Features.vue";
import Hero from "@/components/Home/Hero/Hero.vue";
import Categories from "@/components/Home/Categories/Categories.vue";
import Popular from "@/components/Home/Popular/Popular.vue";
import Testimonials from "../../components/Home/Testimonials/Testimonials.vue";
import Discount from "@/components/Home/Discount/Discount.vue";

export default {
  components: { Features, Hero, Categories, Popular, Testimonials, Discount },
};
</script>

<style></style>
