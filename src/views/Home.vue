<template>
  <div class="home">
    <h1>{{ message }}</h1>
    <section id="topbar" class="d-flex align-items-center">
      <div class="container d-flex justify-content-center justify-content-md-between">
        <div class="contact-info d-flex align-items-center">
          <i class="bi bi-envelope-fill"></i>
          <a href="mailto:contact@example.com">info@example.com</a>
          <i class="bi bi-phone-fill phone-icon"></i>
          +1 5589 55488 55
        </div>
        <div class="social-links d-none d-md-block">
          <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
          <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
          <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
          <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
        </div>
      </div>
    </section>
    <section id="hero" class="d-flex align-items-center">
      <div class="container position-relative" data-aos="fade-up" data-aos-delay="500">
        <h1>Click to Generate!</h1>
        <h2>Click on this button to generate a random word</h2>
        <a href="#about" class="btn-get-started scrollto">Generate</a>
      </div>
    </section>
  </div>
</template>

<style></style>

<script>
export default {
  data: function () {
    return {
      message: "Welcome to Vue.js!",
    };
  },
  created: function () {},
  methods: {},
};
</script>
