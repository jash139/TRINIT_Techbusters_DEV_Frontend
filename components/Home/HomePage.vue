<template>
  <div>
    <TheNavbar />
    <div class="home-page">
      <div class="profile-card">
        <NGOProfileCard />
      </div>
      <div class="ngos-main">
        <HomeMainCard />
      </div>
      <div class="news-events-card">
        <NewsEventsCard />
      </div>
    </div>
  </div>
</template>

<script>
import NGOProfileCard from "../ProfileCards/NGOProfileCard.vue";
import TheNavbar from "../TheNavbar.vue";
export default {
  components: { TheNavbar, NGOProfileCard },
};
</script>

<style scoped>
.home-page {
  display: flex;
  /* display: grid;
  grid-template-columns: auto auto auto; */
  gap: 1rem;
  max-width: 1300px;
  margin: auto;
}
.profile-card {
  position: sticky;
  top: 11vh;
}
.news-events-card {
  position: sticky;
  top: 11vh;
}
</style>