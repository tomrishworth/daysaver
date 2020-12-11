<template>
  <div class="hero">
    <div class="hero-content">
      <g-image src="~/assets/images/daysaver-logo.png" alt="Daysaver Migraine Logo"></g-image>
      <h1>Take Back Your Life.</h1>
      <!-- <p>Help is coming soon...</p> -->
    </div>
  </div>
</template>

<script>
export default {
  metaInfo: {
    title: 'Daysaver Migraine - Save the Day, Take Back Your Life',
  },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@500&display=swap');

.hero {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(38, 38, 37);
  background-image: url('../assets/images/bed.jpg');
  background-size: contain;
  background-repeat: no-repeat;
  background-position: bottom center;
  padding-left: 15px;
  padding-right: 15px;
  color: #c9cbd4;
  font-family: 'Cabin', sans-serif;
  text-align: center;
  @media screen and (min-width: 600px) {
    align-items: start;
  }
  @media screen and (min-width: 1600px) {
    background-size: cover;
  }
}

.hero-content {
  margin-top: -30px;
  @media screen and (min-width: 600px) {
    margin-top: 0;
    padding-top: 8%;
  }
}

.hero img {
  max-width: 100%;
  height: auto;
  display: block;
  margin-bottom: 3rem;
  @media screen and (max-width: 599px) {
    width: 280px;
  }
}

.hero h1 {
  font-size: 1.5rem;
  margin-bottom: 0;
}

.hero p {
  font-size: 1.5rem;
  margin: 0;
  opacity: 0.5;
}

@media screen and (min-width: 600px) {
  .d-sm-none {
    display: none;
  }
}
</style>
