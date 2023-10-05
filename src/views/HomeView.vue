<template>
  <div class="home">
    <HeaderComponent></HeaderComponent>
    <HomePage />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from "@/components/HeaderComponent.vue";
import HomePage from "@/components/HomePage.vue";
export default {
  name: "HomeView",
  components: {
    HeaderComponent,
    HomePage,
  },
};
</script>
