<template>
  <section class="home" id="home">
    <div class="home-content">
      <h1>Hi, I'm Mv</h1>
      <h3>Web Developer</h3>
      <div class="btn-box">
        <router-link to="/about">about</router-link>
        <router-link to="/project">Projects</router-link>
      </div>
    </div>
    <div class="home-socials">
      <a href="#"><i class="bx bxl-linkedin"></i></a>
      <a href="#"><i class="bx bxl-facebook-circle"></i></a>
      <a href="#"><i class="bx bxl-instagram-alt"></i></a>
    </div>
  </section>
</template>

<script>
export default {
  name: "HomeSection",
};
</script>

<style>
@import "../styles/home.css";
</style>
