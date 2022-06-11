<template>
  <footer class="footer">
    <div class="footer__content container">
      <div class="footer__about">
        <h2>Fhasion</h2>
        <p>
          There are many variations of passages of Lorem Ipsum available, but
          the majority have suffered alteration.
        </p>
        <ul class="footer__redes">
          <li><img src="../../assets/icons/facebook.svg" alt="" /></li>
          <li><img src="../../assets/icons/instagram.svg" alt="" /></li>
          <li><img src="../../assets/icons/twitter.svg" alt="" /></li>
        </ul>
      </div>
      <div>
        <h3>Useful Links</h3>
        <ul class="footer__list">
          <li><a href="#">Your Account</a></li>
          <li><a href="#">Products</a></li>
          <li><a href="#">Become Affiliate</a></li>
          <li><a href="#">Help</a></li>
        </ul>
      </div>
      <div>
        <h3>Contact Us</h3>
        <ul class="footer__list">
          <li><a href="#">fashion@gmail.com</a></li>
          <li><a href="#">+11 1111-1111</a></li>
        </ul>
      </div>
      <div class="newsletter">
        <h3>Newsletter</h3>
        <p>There are many variations of passages of Lorem Ipsum available.</p>
        <form action="#">
          <input
            type="email"
            id="newsletterEmail"
            name="newsletterEmail"
            placeholder="Digite seu melhor E-mail"
          />
        </form>
      </div>
    </div>
    <p class="copy container">© All rights reserved</p>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
@import "./Footer.css";
</style>
