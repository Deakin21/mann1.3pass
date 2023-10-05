<template>
  <div class="home"><HeaderComponent /> <AboutPage /></div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from "@/components/HeaderComponent.vue";
import AboutPage from "@/components/AboutPage.vue";
export default {
  name: "HomeView",
  components: {
    HeaderComponent,
    AboutPage,
  },
};
</script>
