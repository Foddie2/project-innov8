<template>
  <div class="hero-image">
    <div class="hero-text">
        <p class="snippet">Do you have an <strong>innovative business idea</strong> that addresses our most pressing <strong>challenges?</strong></p>
      <button class="button btn">APPLY NOW</button>
    </div>


  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
 .hero-image {
   background-image: src="~assets/images/hero.jpg";
  /* height: 60vh; */
  position: relative;
  display: flex;
  padding: 5rem 0;
  align-items: flex-start;
  justify-content: space-between;
    }
    .hero-text {
        width: 49%;
        margin-top: 5rem;
    }
    /* .header {
        font-weight: 900;
        font-size: 5rem;
    } */
    .snippet {
        color:#0133A1;
        font-size: 2.0rem;
    }
    .image {
        width: 27.5rem;
        margin-top: 2rem;
    }
    /* .overlay {
        background: rgba(0, 0, 0, 0);
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
    } */
    .button {
        padding: 1rem 1rem;
        /* border-radius: 100rem; */
        background-color: #0133A1;
        color: white;
        /* width: 8rem; */
        font-weight: 700;
        transition: 0.5s;
    }

    @media (max-width: 500px) {
        .Hero {
            height: 50vh;
        }
    }

    .img {
      width: 100px;
      height: 100px;
      margin-left: 50%;
      transform: translate(-50%, 0);
  }

</style>
