<template>
  <section class="categories container">
    <h2 class="subtitle">Categories</h2>
    <div class="categories__card">
      <div>
        <img :src="require('../../../assets/img/categories.jpg')" />
      </div>
      <div>
        <img :src="require('../../../assets/img/categories-2.jpg')" />
      </div>
      <div>
        <img :src="require('../../../assets/img/categories-3.jpg')" />
      </div>
    </div>
    <a href="#" class="btn">See More</a>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
@import "./Categories.css";
</style>
