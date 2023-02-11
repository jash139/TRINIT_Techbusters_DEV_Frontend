<template>
  <div class="home-main-card">
    <div class="search-bar">Search bar</div>
    <TopNGOs />
    <SearchResults />
  </div>
</template>

<script>
import SearchResults from "./SearchResults.vue";
import TopNGOs from "./TopNGOs.vue";
export default {
  components: { TopNGOs, SearchResults },
};
</script>

<style scoped>
.home-main-card {
  background-color: white;
  border-radius: 5px;
  max-width: 750px;
  width: 100%;
}
</style>