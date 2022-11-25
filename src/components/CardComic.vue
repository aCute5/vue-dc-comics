<template>
  <div class="card">
    <img :src="comic.thumb" />
    <div class="card-body">
      <h5 class="card-title">{{ comic.series }}</h5>
      <p class="card-text">
        {{ comic.type }}
      </p>
      <a href="#" class="btn btn-primary">{{ comic.price }}</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardComic",
  props: {
    comic: Object,
  },
};
</script>

<style lang="scss" scoped>
.card-text {
  font-size: 0.5rem;
}
.card-title {
  font-size: 1rem;
}
.card-body {
  padding: 0;
  font-size: 0.5rem;
}
.btn {
  font-size: 0.8rem;
}
</style>
