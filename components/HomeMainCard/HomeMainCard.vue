<template>
  <div class="home-main-card">
    <div class="search-bar">
      <input
        class="search-box"
        type="text"
        placeholder="Search"
        name="search"
        v-model="searchValue"
        @change="updateSearchResults"
      />
    </div>
    <TopNGOs />
    <SearchResults />
  </div>
</template>

<script>
import SearchResults from "./SearchResults.vue";
import TopNGOs from "./TopNGOs.vue";
export default {
  components: { TopNGOs, SearchResults },
  data() {
    return {
      searchValue: "",
    };
  },
  methods: {
    updateSearchResults() {
      // call api to update search results and pass as prop to <SearchResults />
    },
  },
};
</script>

<style scoped>
.home-main-card {
  background-color: white;
  border-radius: 5px;
  max-width: 750px;
  width: 100%;
}
.search-bar {
  padding: 1.5rem;
}
.search-box {
  border: none;
  outline: none;
  padding: 1rem;
  background-color: rgb(241, 241, 241);
  border-radius: 5rem;
  width: 100%;
}
</style>