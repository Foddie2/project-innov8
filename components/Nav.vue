<template>
  <div class="nav-container">
<div class="Nav">
    <nav class="navbar navbar-expand-md navbar-light bg-white">
        <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
           <a href="#" class="navbar-brand">
            <img class="logo-img" src="~assets/images/Svg/Innov8 Logo.svg" alt="Logo">
        </a>
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
    </ul>
  </div>
    </nav>

</div>

</div>
</template>

<script>
  export default  {



  }
</script>

<style >
.nav-container{
  z-index: 100;
	position:sticky;
	top:0;

}


.active a {
        color: black;
        font-weight: bold;
    }

.logo-img{
  height: 100%;
  width: 9rem;

}

.bg-white {
	position:sticky;
	top:0;
  border-bottom: 3px solid #0133A1;
}
.navbar-brand{
  color: #0133A1 !Important;
}

.navbar-nav li a {
color: #0133A1 !Important;
}

.navbar .navbar-nav .nav-link:hover {
  color: #000000;
}
/* @media only screen and (min-width: 960px) {
  .navbar .navbar-nav .nav-link {
    padding: 1em 0.7em;
  }
  .navbar {
    padding: 0;
  }
  .navbar .navbar-brand {
    padding: 0 0.7em;
  }
} */
.navbar .navbar-nav .nav-link {
  position: relative;
}
.navbar .navbar-nav .nav-link::after {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  background-color: #F90990;
  color: transparent;
  width: 0%;
  content: '';
  height: 3px;
  transition: all 0.5s;
}
.navbar .navbar-nav .nav-link:hover::after {
  width: 100%;
}


</style>
