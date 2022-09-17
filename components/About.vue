<template>
  <div>
    <section class="about-section">
      <div class="container text-p ">
        <div class="text-container row">
          <div
            id="about"
            class="col-md-6 col-12 col-lg-6 text-area order-sm-first"
          >
            <h5 class="title">About <strong>Project Innov8</strong></h5>
            <p class="text">
              The internal innovation challenge is an opportunity for bold
              Stanbic staff to form cross-departmental teams that are determined
              to develop new ideas meant to address customer-centric challenges.
              <br />
              The challenge is open to all Stanbic staff with 30 staff members,
              in 10 teams of 3 individuals, selected to participate in the
              program.
              <br />
              During the program, Stanbic Innovators will be
              supported through the process of interrogating their ideas,
              developing business models, and pitching them to the bank.
              <br />
              <br />
              During the final pitch a winning team and 2 runners up will be
              selected. Walking away with $10,000, $5,000 and $2,500 in prizes,
              respectively.
            </p>
            <h6 class="innovation-text">
              <strong>Innovation challenge outcomes</strong>
            </h6>
            <p class="mb-md-4">Innovation-ready Change Makers</p>
          </div>
          <div class="col-md-6 col-12 col-lg-6 p-0 about-image" />
        </div>
      </div>
    </section>


    <section class="about-section">
      <div class="container text-p ">

        <div class="text-container row">
           <div class="col-md-6 col-12 col-lg-6 p-0 about-image" />
          <div
            id="about"
            class="col-md-6 col-12 col-lg-6 text-area order-sm-last"
          >
            <h5 class="title">About <strong>Project Innov8</strong></h5>
            <p class="text">
              The internal innovation challenge is an opportunity for bold
              Stanbic staff to form cross-departmental teams that are determined
              to develop new ideas meant to address customer-centric challenges.
              <br />
              The challenge is open to all Stanbic staff with 30 staff members,
              in 10 teams of 3 individuals, selected to participate in the
              program. <br />During the program, Stanbic Innovators will be
              supported through the process of interrogating their ideas,
              developing business models, and pitching them to the bank. <br />
              <br />
              During the final pitch a winning team and 2 runners up will be
              selected. Walking away with $10,000, $5,000 and $2,500 in prizes,
              respectively.
            </p>
            <h6 class="innovation-text">
              <strong>Innovation challenge outcomes</strong>
            </h6>
            <p class="mb-md-4">Innovation-ready Change Makers</p>
          </div>

        </div>
      </div>
    </section> 

    <section class="eligibility-section" id="eligibility">
      <div class="container ">
        <div class="text-container row">
          <div class="col-md-6 col-12 col-lg-6 p-0 eligibility-image" />
          <div class="col-md-6 col-12 col-lg-6 eligibility-text-wrapper">
            <div id="triangle" class="d-none d-md-block" />
            <h5 class="title ml-4">Eligibility <strong>Criteria</strong></h5>
            <ul>
              <li>
                The submitting team must be <strong>Stanbic Bank Zambia</strong>
              </li>
              <li>
                Team Members can
                <strong>not belong to more than one innovation</strong>
              </li>
              <li>
                The submitting team must be <strong>based in Zambia</strong>
              </li>
              <li>
                The submitted
                <strong>idea must be aligned with the needs of</strong>
              </li>
              <li>
                The submitting team <strong> must be made up of Zambian</strong>
              </li>
              <li>
                The submitting team may be
                <strong>seeking support to customer</strong>
              </li>
              <li>
                <strong>A maximum of 2 team members</strong> (preferably Team
                Leads) must be able to attend the sprint week
              </li>
              <li>
                The winning team of the incubation programme must be able to
                attend a <strong>4-week idea development programme in</strong>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
#triangle {
  top: 10px;
  left: -100px;
  position: absolute;
  background-color: #f3f3f4;
  clip-path: polygon(100% 0, 71% 19%, 100% 39%);
  width: 100px;
  height: 100px;
}
.about-section {
  background: #f3f3f4;
  padding: 1em;
  position: relative;
}

.title {
  color:#4B38A9;
  animation: color 30s linear infinite;
}

@keyframes color {
  33.3% { color: #E00D93; }
  66.7% { color: #4B38A9; }
}

/*|||||||||||||||||||||||||| */

body:before {
  content: "";
  position: absolute;
  display: block;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  opacity: .1;
  background-color: currentColor;
  background-image: linear-gradient(to bottom, currentColor, #fff);
}

p, h1 {
  color: black;
  margin-top: 0;
}



.eligibility-section {
  margin: 3em 0;
  position: relative;
}
.text-area {
  background-color: #fff;
  padding: 20px;
}
.eligibility-text-wrapper {
  background-color: #f3f3f4;
  padding: 20px;
  position: relative;
}
.eligibility-text-wrapper::before {
  content: "";
  position: absolute;
  border-color: #0133a1;
  border-style: solid;
  border-width: 0px 0.3em 5em 0px;
  height: 1em;
  bottom: 0em;
  right: -0.8em;
  margin-top: -1em;
  transform: rotate(0deg);
  width: 0.8em;
}

.text-area::after {
  content: "";
  position: absolute;
  border-color: #0133a1;
  border-style: solid;
  border-width: 0px 0.3em 5em 0px;
  height: 1em;
  bottom: 0em;
  left: -0.8em;
  margin-top: -1em;
  transform: rotate(0deg);
  width: 0.8em;
}

.text-container {
  background-color: #f3f3f4;
  margin: 3em 0;
}
.about-image {
  background-image: url("~assets/images/online-class.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.eligibility-image {
  background-image: url("~assets/images/person-text.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.innovation-text {
  font-size: 16px;
  margin-top: 1em;
}
p {
  font-weight: normal;
  margin-bottom: 0;
}
h5,
h6 {
  color: #0133a1;
}


</style>
