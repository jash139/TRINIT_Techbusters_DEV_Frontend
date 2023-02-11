<template>
  <div>
    <TheNavbar />
    <NGOProfileCard />
    <!-- <PhilanthropistProfileCard /> -->
  </div>
</template>

<script>
import NGOProfileCard from "~/components/ProfileCards/NGOProfileCard.vue";
import PhilanthropistProfileCard from "~/components/ProfileCards/PhilanthropistProfileCard.vue";

export default {
  components: { PhilanthropistProfileCard, NGOProfileCard },
  name: "IndexPage",
};
</script>
