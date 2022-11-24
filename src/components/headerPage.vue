<template>
  <header class="header">
    <ul class="nav-elements">
      <img src="@/img/dc-logo.png" alt="" />
      <li>Ciao</li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "headerPage",
};
</script>

<style lang="scss" scoped>
$dcblue_color: #175793;
.header {
  color: rgb(255, 255, 255);
  display: flex;
  justify-content: space-between;
  height: 20vh;
}
</style>
