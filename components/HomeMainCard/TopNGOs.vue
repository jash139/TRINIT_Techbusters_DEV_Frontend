<template>
  <div class="top-ngos-card">
    <p class="hidden-content">
      Philanthropic organizations use their resources to improve society and
      need to be equipped to do so whenever required.
    </p>
    <button type="button" id="top-ngo-card" @click="toggleTopNGOs">
      Top NGOs
    </button>
    <div class="content">
      <NGODisplayCard />
      <NGODisplayCard />
    </div>
  </div>
</template>

<script>
import NGODisplayCard from "./NGODisplayCard.vue";
export default {
  components: { NGODisplayCard },
};
</script>

<style scoped>
.top-ngos-card {
  padding: 1rem;
}
.top-ngos-card button {
  cursor: pointer;
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
.hidden-content {
  opacity: 0;
  line-height: 0;
}
</style>