<template>
  <div class="home-main-card">
    <div class="search-bar">Search bar</div>
    <TopNGOs />
  </div>
</template>

<script>
import TopNGOs from "./TopNGOs.vue";
export default {
  components: { TopNGOs },
};
</script>

<style scoped>
.home-main-card {
  background-color: white;
  max-width: 750px;
  width: 100%;
}
</style>