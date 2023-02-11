<template>
  <div class="search-results">
    <button type="button">Search Results (2)</button>
    <div class="content">
      <NGODisplayCard />
      <NGODisplayCard />
      <NGODisplayCard />
    </div>
  </div>
</template>

<script>
import NGODisplayCard from "./NGODisplayCard.vue";

export default {
  components: { NGODisplayCard },
  methods: {},
};
</script>

<style scoped>
.search-results {
  padding: 1rem;
}
.search-results button {
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  background-color: white;
  font-size: 1.25rem;
  padding: 1rem;
}
.content {
  padding: 0 1rem;
  display: block;
  overflow: hidden;
}
</style>