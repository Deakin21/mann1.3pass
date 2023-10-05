<template>
  <header class="header">
    <router-link class="logo" to="/">MV.</router-link>
    <nav class="navbar">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/project">Project</router-link>
      <router-link to="/contact">Contact</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style>
@import "../styles/header.css";
</style>
