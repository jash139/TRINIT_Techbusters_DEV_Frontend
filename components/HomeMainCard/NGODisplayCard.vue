<template>
  <div class="ngo-card">
    <div class="profile-image">
      <svg
        width="25"
        height="25"
        viewBox="0 0 25 25"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M12.2834 23.4411C18.5282 23.4411 23.5907 18.3786 23.5907 12.1338C23.5907 5.88893 18.5282 0.826477 12.2834 0.826477C6.03853 0.826477 0.976074 5.88893 0.976074 12.1338C0.976074 18.3786 6.03853 23.4411 12.2834 23.4411Z"
          stroke="black"
          stroke-width="1.5"
          stroke-miterlimit="10"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <path
          d="M12.283 15.0356C8.78074 15.0356 5.7788 17.0369 4.27783 20.0389C6.27912 22.1402 9.181 23.341 12.283 23.341C15.385 23.341 18.2869 22.0402 20.2882 20.0389C18.7872 17.137 15.7853 15.0356 12.283 15.0356Z"
          stroke="black"
          stroke-width="1.5"
          stroke-miterlimit="10"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <path
          d="M12.283 12.434C14.2725 12.434 15.8853 10.8212 15.8853 8.83165C15.8853 6.84214 14.2725 5.22932 12.283 5.22932C10.2935 5.22932 8.68066 6.84214 8.68066 8.83165C8.68066 10.8212 10.2935 12.434 12.283 12.434Z"
          stroke="black"
          stroke-width="1.5"
          stroke-miterlimit="10"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </div>
    <div class="profile-details">
      <h5 class="name">NGO Name</h5>
      <p class="agenda">
        Lorem ipsum dolor sit amet, csectetur adipiscid olor sit amet, csectetur
        adipiscidolor sit amet, csectetur adipiscidolor sit amet, csectetur
        adipiscida dese
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.ngo-card {
  display: flex;
  border-bottom: 1px solid rgb(211, 211, 211);
  margin-bottom: 1rem;
}
.profile-image {
  margin-right: 1rem;
}
.name {
  margin: 0;
  padding: 0;
  font-weight: 600;
}
.agenda {
  font-size: 0.8rem;
}
</style>