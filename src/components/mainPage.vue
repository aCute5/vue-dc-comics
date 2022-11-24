<template>
  <section class="black-section">
    <div class="content">
      <h2>--> Content go here</h2>
    </div>
    <div class="shop">
      <img src="@/img/buy-comics-digital-comics.png" alt="" />
      <h4>DIGITAL COMICS</h4>
      <img src="@/img/buy-comics-merchandise.png" alt="" />
      <h4>MERCHANDISE</h4>
      <img src="@/img/buy-comics-subscriptions.png" alt="" />
      <h4>SUBSCRIPTIONS</h4>
      <img src="@/img/buy-comics-shop-locator.png" alt="" />
      <h4>LOCATOR</h4>
      <img src="@/img/buy-dc-power-visa.svg" alt="" />
      <h4>LOCATOR</h4>
    </div>
  </section>
</template>

<script>
export default {
  name: "mainPageVue",
};
</script>

<style lang="scss" scoped>
.content {
  background-color: black;
  height: 20vh;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 40px;
}
.black-section .shop {
  display: flex;
  justify-content: center;
  gap: 1rem;
  height: 20vh;
  background-color: #0282f9;
  color: rgb(255, 255, 255);
  align-items: center;
}
.shop img {
  width: 4rem;
}
.shop h4 {
  font-size: 1rem;
}
</style>
