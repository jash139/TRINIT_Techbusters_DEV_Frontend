<template>
  <div>
    <the-nav-bar />
    <div class="home-page">
      <div class="profile-card">
        <NGOProfileCard />
      </div>
      <div class="news-events-card">
        <NewsEventsCard />
      </div>
    </div>
  </div>
</template>

<script>
import NGOProfileCard from "../ProfileCards/NGOProfileCard.vue";
import TheNavBar from "../TheNavBar.vue";
export default {
  components: { TheNavBar, NGOProfileCard },
};
</script>

<style scoped>
.home-page {
  display: grid;
  grid-template-columns: auto auto auto;
  max-width: 1300px;
  margin: auto;
}
.profile-card {
  position: sticky;
  top: 10vh;
}
</style>