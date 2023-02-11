<template>
  <div class="profile-page">
    <the-navbar />
    <div class="profile-card">
      <!-- <NGOProfile /> -->
      <PhilanthropistProfile />
    </div>
  </div>
</template>

<script>
import NGOProfile from "~/components/ProfilePageCard/NGOProfile.vue";
import PhilanthropistProfile from "~/components/ProfilePageCard/PhilanthropistProfile.vue";
import TheNavbar from "~/components/TheNavbar.vue";

export default {
  components: { NGOProfile, PhilanthropistProfile, TheNavbar },
};
</script>

<style scoped>
</style>