<template>
  <div class="hero">
    <div>
      <img src="https://res.cloudinary.com/mahana/image/upload/v1606767323/Website/daysaver-logo_bl3icj.png" />
      <h1>
        Save the Day,<br class="d-sm-none" />
        Take Back Your Life
      </h1>
      <p>Help is coming soon...</p>
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

<style>
@import url('https://fonts.googleapis.com/css2?family=Cabin:wght@500&display=swap');

.hero {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(38, 38, 37);
  padding-left: 15px;
  padding-right: 15px;
  color: #c9cbd4;
  font-family: 'Cabin', sans-serif;
  text-align: center;
}

.hero img {
  max-width: 100%;
  height: auto;
  display: block;
  margin-bottom: 3rem;
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
