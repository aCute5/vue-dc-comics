<template>
  <div class="containermine">
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
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.containermine {
  margin: 0;
  padding: 0;
  font-family: "Lato", sans-serif;
  box-sizing: border-box;
}
</style>
