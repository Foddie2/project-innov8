<template>
  <div class="container">

<div class="Nav">
    <nav class="navbar navbar-expand-md navbar-light bg-white">
        <a href="#" class="navbar-brand">
            <img class="logo-img" src="~assets/images/Svg/Innov8 Logo.svg" alt="Logo">
        </a>
        <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav mx-auto">
      <li class="nav-item active">
        <a class="nav-link active" href="#about">About <span class="sr-only" font-weight-bold>(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#eligibility">Eligibility Criteria</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#benefits">Benefits</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#stages">Stages</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#faq">FAQ</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#contacts">Contacts</a>
      </li>
    </ul>
       <ul class="nav navbar-nav navbar-right">
         <svg  xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#0133A1" class="bi bi-person-fill" viewBox="0 0 16 16">
  <path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
</svg>
        <!-- <img class="logo-img-icon" src="~assets/images/user.png" alt="Logo"> -->
    </ul>
  </div>
    </nav>

</div>

</div>
</template>

<script>
  export default {

  }
</script>

<style >
.active a {
        color: black;
        font-weight: bold;
    }

.logo-img{
  height: 100%;
  width: 9rem;

}
.navbar-brand{
  color: #0133A1 !Important;
}

.navbar-nav li a {
color: #0133A1 !Important;
}


</style>
