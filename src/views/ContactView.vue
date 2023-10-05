<template>
  <div class="home"><HeaderComponent /> <ContactPage /></div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from "@/components/HeaderComponent.vue";
import ContactPage from "@/components/ContactPage.vue";
export default {
  name: "HomeView",
  components: {
    HeaderComponent,
    ContactPage,
  },
};
</script>
