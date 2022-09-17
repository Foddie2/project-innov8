<template>
  <section class="bg-image">
    <div class="container">
      <div class="hero-text">
        <p class="snippet">
          Do you have a <strong>big blue idea</strong> that addresses our most pressing challenges
        </p>
        <button class="button btn mt-4">APPLY NOW</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.bg-image {
  background-image: url("~assets/images/hero-bg.jpg");
  min-height: 500px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  background-attachment: fixed;
  transition: 0.5s;
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.hero-text {
  max-width: 630px;
  color: #0133a1;
}
.snippet {
  color: #0133a1;
  font-size: 2.5rem !important;
}

.image {
  width: 27.5rem;
  margin-top: 2rem;
}
.button {
  padding: 1rem 1rem;
  background-color: #0133a1;
  color: white;
  font-weight: 700;
  transition: 0.4s all;
}
.button:hover {
  background-color: #e1dbdf;
  color: #0133a1;
  border: 1px solid #0133a1;
}
@media (max-width: 500px) {
  .Hero {
    min-height: 50vh;
  }
}
.snippet {
  font-size: 1.5em;
}

.img {
  width: 100px;
  height: 100px;
  margin-left: 50%;
  transform: translate(-50%, 0);
}
</style>
