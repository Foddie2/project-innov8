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
        <a class="nav-link active" href="#">About <span class="sr-only" font-weight-bold>(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Eligibility Criteria</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Benefits</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Stages</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">FAQ</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contacts</a>
      </li>
    </ul>
       <ul class="nav navbar-nav navbar-right">
         <a href="#"><i class="bi bi-person-fill"></i> Login</a>
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
