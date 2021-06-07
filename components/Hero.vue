<template>
<section class="bg-image">
  <div class="hero-image container">
    <div class="hero-text">
        <p class="snippet">Do you have an <strong>innovative business idea</strong> that addresses our most pressing <strong>challenges?</strong></p>
      <button class="button btn mt-4">APPLY NOW</button>
    </div>


  </div>
  </section>
</template>

<script>
  export default {

  }
</script>

<style scoped>
 .bg-image {
   background-image: url("~assets/images/hero-bg.jpg");
   width: 100%;
  height: 32em;
  position: relative;
  display: flex;
  padding-top: 42%;

  padding: 0.5rem 0;
  align-items: flex-start;
  justify-content: space-between;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  background-attachment: fixed;
  transition: 0.5s;

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
        font-size: 2.0rem !Important;
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
        transition: 0.4s all;
    }

    /* .bg-image:hover .button{
      transition: 0.5s all;
      width: 250px;
    }
    .bg-image .button:hover{
       width: 130px;
    } */
  /* .button::after{
    content:'';
    position: absolute;
    left: -20%;
    right: -20%;
    top:0;
    transform: skewX(-45deg) scale(0,1);
  }
  .button:hover::after{
    transform: skewX(-45deg) scale(1,1);
  } */

  .button:hover{
    background-color: #E1DBDF;
    color: #0133A1;
    border: 1px solid #0133A1 ;

  }
    @media (max-width: 500px) {
        .Hero {
            min-height: 50vh;
        }
    }
    /* .hero-text {
      margin-top: 1em;
    } */
    .snippet{
      font-size: 1.5em ;
    }
    .img {
      width: 100px;
      height: 100px;
      margin-left: 50%;
      transform: translate(-50%, 0);
  }

</style>
