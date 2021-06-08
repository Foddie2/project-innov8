<template>
  <section class="bottom-links">
    <div class="container">
      <div class="row">
        <div class="col-md-6 logo-links">
          <h5>An initiative of</h5>
        </div>
        <div class="col-md-6 partners">
          <div class="d-md-flex">
            <img
              class="partner-icon mr-md-4"
              src="~assets/images/Svg/stanbic.svg"
              alt="Logo"
            />
            <img
              class="partner-icon"
              src="~assets/images/Svg/BH logo Alt innovations black.svg"
              alt="Logo"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.bottom-icon {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  height: 3em;
}
.partners {
  padding: 0 4em;
}
.partner-icon {
  max-width: 200px;
  max-height: 200px;
}
.bottom-links {
  background-color: #f3f3f4;
  padding: 4rem;
}

.logo-links {
  display: flex;
  justify-content: center;
  align-items: center;
}

@media (max-width: 500px) {
  .bottom-icon {
    margin-top: 2em;
  }
}
</style>
