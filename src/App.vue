<template>
  <div class="container">
    <headerPage></headerPage>
    <mainPage></mainPage>
    <footerPage></footerPage>
  </div>
</template>

<script>
import headerPage from "@/components/headerPage.vue";
import mainPage from "./components/mainPage.vue";
import FooterPage from "./components/footerPage.vue";
export default {
  components: {
    headerPage,
    mainPage,
    FooterPage,
  },
};
</script>

<style lang="scss">
.container {
  font-family: "Lato", sans-serif;
  height: 100vh;
}
</style>
