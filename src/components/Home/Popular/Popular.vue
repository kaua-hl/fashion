<template>
  <section class="popular">
    <div class="popular__content container">
      <img
        :src="require('../../../assets/img/popular.jpg')"
        alt="image popular section"
      />
      <div class="popular__description">
        <h2 class="subtitle">Contrary to popular belief, Lorem</h2>
        <p>
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book.
        </p>
        <a href="#" class="btn">See More</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
@import "./Popular.css";
</style>
