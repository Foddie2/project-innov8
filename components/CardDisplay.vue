<template>
<div>
<section class="card-section">
<div class="container ">
  <div class="text-container col-md-10 mx-auto" >

  <div class="col-md-6 text-area order-sm-first">
    <h5 class="title">About <strong>Project Innov8</strong></h5>
      <p class="text">The internal innovation challenge is an opportunity for bold Stanbic staff to form cross-departmental teams that are determined to develop new ideas meant to address customer-centric challenges. <br> The challenge is open to all Stanbic staff with 30 staff members, in 10 teams of 3 individuals, selected to participate in the program. <br>During the program, Stanbic Innovators will be supported through the process of interrogating their ideas, developing business models, and pitching them to the bank. <br> <br> During the final pitch a winning team and 2 runners up will be selected. Walking away with $10,000, $5,000 and $2,500 in prizes, respectively.</p>
        <h5><strong>Innovation challenge outcomes</strong></h5>
        <p>Innovation-ready Change Makers</p>
      </div>
    <div>
      <img src="~assets/images/online-class.jpg"/>
    </div>
  </div>

</div>
</section>

<div class="container ">
  <div class="text-container col-md-10 mx-auto" >
  <div class="col-md-6 mt-3 title-text order-sm-last">
          <h5 class="title ml-4">Eligibility <strong>Criteria</strong></h5>
          <ul>
            <li>The submitting team must be <strong>Stanbic Bank Zambia</strong></li>
            <li>Team Members can <strong>not belong to more than one innovation</strong></li>
            <li>The submitting team must be <strong>based in Zambia</strong></li>
            <li>The submitted <strong>idea must be aligned with the needs of</strong></li>
            <li>The submitting team <strong> must be made up of Zambian</strong></li>
            <li>The submitting team may be <strong>seeking support to customer</strong></li>
            <li><strong>A maximum of 2 team members</strong> (preferably Team Leads) must be able to attend the sprint week</li>
            <li> The winning team of the incubation programme must be able to attend a <strong>4-week idea development programme in</strong></li>
          </ul>
        </div>
    <div>
      <img src="~assets/images/person-text.jpg"/>
    </div>
  </div>

</div>
</div>



</template>

<script>
  export default {

  }
</script>

<style >

.title-text{
  padding: 1em;
}

.card-section{
  background:#F3F3F4;;
  padding:1em;
  position: relative;

}
.text-area{
  background-color: #fff;


}
.title-text::before{
 content: '';
  position: absolute;
  border-color: #0133A1;
  border-style: solid;
  border-width: 0px 0.3em 5em 0px;
  height: 1em;
  bottom: 0em;
  right: -1.4em;
  margin-top: -1em;
  transform: rotate(0deg);
  width: 0.5em;

}

.text-area::after{
 content: '';
  position: absolute;
  border-color: #0133A1;
  border-style: solid;
  border-width: 0px 0.3em 5em 0px;
  height: 1em;
  top: 24em;
  left: -0.6em;
  margin-top: -1em;
  transform: rotate(0deg);
  width: 0.5em;

}


.text-container{
  display: flex;
  margin: 4rem;
  background-color: #F3F3F4;
  display:flex;
}

img{
  height: 100%;
  width: 28rem;
  object-fit: cover;
}

h5{
  color: #0133A1;
}
p{
  font-weight: normal;
  margin-bottom: 0;
}

</style>
