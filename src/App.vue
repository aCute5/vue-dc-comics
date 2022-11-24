<template>
  <headerPage></headerPage>
  <mainPageVue></mainPageVue>
</template>

<script>
import headerPage from "@/components/headerPage.vue";
import mainPageVue from "./components/mainPage.vue";
export default {
  components: {
    headerPage,
    mainPageVue,
  },
};
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: content-box;
}
</style>
