<template>
  <div class="home"><HeaderComponent /> <ProjectPage /></div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from "@/components/HeaderComponent.vue";
import ProjectPage from "@/components/ProjectPage.vue";
export default {
  name: "HomeView",
  components: {
    HeaderComponent,
    ProjectPage,
  },
};
</script>
