<template>
  <div class="news-events-card">
    <h3 class="heading">News & Events</h3>
    <div class="events">
      <div class="event">
        <p class="name">NGO Name</p>
        <p class="news">
          Lorem ipsum dolor sit amet, csectetur adipe.
          <span class="read-more-btn">Read more</span>
        </p>
      </div>
      <div class="event">
        <p class="name">NGO Name</p>
        <p class="news">
          Lorem ipsum dolor sit amet, csectetur adipe.
          <span class="read-more-btn">Read more</span>
        </p>
      </div>
      <div class="event">
        <p class="name">NGO Name</p>
        <p class="news">
          Lorem ipsum dolor sit amet, csectetur adipe.
          <span class="read-more-btn">Read more</span>
        </p>
      </div>
      <div class="event">
        <p class="name">NGO Name</p>
        <p class="news">
          Lorem ipsum dolor sit amet, csectetur adipe.
          <span class="read-more-btn">Read more</span>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.news-events-card {
  background-color: white;
  max-width: 280px;
  width: 100%;
  padding: 2rem 1.5rem;
  border-radius: 5px;
}
.heading {
  margin-top: 0;
  font-size: 1rem;
}
.name {
  font-size: 1rem;
  font-weight: 600;
}
.news {
  color: rgb(124, 124, 124);
  font-size: 0.8rem;
  line-height: 1.5;
}
.event {
  border-bottom: 1px solid rgb(226, 226, 226);
}
.read-more-btn {
  color: blueviolet;
  cursor: pointer;
  text-decoration: underline;
  margin-left: 0.25rem;
}
</style>