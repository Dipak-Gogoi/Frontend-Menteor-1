<template>
  <div class="Home-page">
    <div class="container">

      <section id="heading">
        <div class="">
          <h1 class="head-tag">Relaible, efficient delivery</h1>
          <h1>Powered by Technology</h1>
          <p class="sub-head">Our Artificial Intelligence powered tools use millions of project data points to ensure that your project is successful</p>
        </div>
      </section>
  
      <section id="cards">
        <div class="work">
          <div class="row">
            <div class="col-md-4 card1">
              <div class="supervisor card">
                <h3>Supervisor</h3>
                <p>Monitors activity to identify project roadblocks</p>
                <img src="../assets/icon-supervisor.svg" alt="Supervisor">
              </div>
            </div>
            <div class="col-md-4">
              <div class="team card">
                <h3>Team Builder</h3>
                <p>Scan our talent network to create the optimal team for your project</p>
                <img src="../assets/icon-team-builder.svg" alt="Supervisor">
              </div>
              <div class="card2">
              <div class="karma card">
                <h3>Karma</h3>
                <p>Regularly evaluate our talent to ensure quality</p>
                <img src="../assets/icon-karma.svg" alt="Supervisor">
              </div>
              </div>
            </div>
            <div class="col-md-4 card3">
              <div class="calculator card">
                <h3>Calculator</h3>
                <p>Uses data from past projects to provide better delivery estimates</p>
                <img src="../assets/icon-calculator.svg" alt="Supervisor">
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Home',
  
  
    // data(){
    //   return{
    //     work: [],
    //   }
    // },
    // created(){
    //   this.initialiseworkData();
    // },
    // methods:{
    //   initialiseworkData(){
    //     this.work =[{
    //       title: "Supervisor",
    //       tag: "Monitors activity to identify project roadblocks",
    //       imageName: "icon-supervisor.svg"
    //     },
    //     {
    //       title: "Team",
    //       tag: "",
    //       imageName: ""
    //     },
    //     {
    //       title: "",
    //       tag: "",
    //       imageName: ""
    //     },
    //     {
    //       title: "",
    //       tag: "",
    //       imageName: ""
    //     }]
    //   }
    // }
  
  }
</script>

<style>
.Home-page{
  background-color: hsl(0, 0%, 98%)
}

p{
  color: gray;
}
  .head-tag {
    padding-top: 5%;
    font-weight: 200;
  }
  
  .sub-head {
    text-align: center;
    line-height: 1.9rem;
    width: 45%;
    margin: auto;
    padding-top: 2%;
  }
  
  .work {
    padding-top: 5%;
  }
  
  .card {
    box-shadow: 0px 20px 30px  hsl(229, 6%, 66%);
    padding: 7% 2% 7% 10%;
    text-align: left;
    /* font-size: 14PX; */
    /* border-top-width: 6px;
    border-top-color: #1bbc9b; */
  }
  
  .card img{
    width: 60px;
    margin-left: 230px;
  }
  
  .card1{
    padding-top: 11%;
  }
  .supervisor{
    border-top-width: 4px;
    border-top-color:  hsl(180, 62%, 55%);
    
  }
  .card2{
    padding-top: 10%;
  }

  .team {
    border-top-width: 4px;
    border-top-color: hsl(0, 78%, 62%);
  }

  .karma{
    border-top-width: 4px;
    border-top-color:hsl(34, 97%, 64%);
  }

  .card3{
    padding-top: 11%;
  }
  .calculator{
     border-top-width: 4px;
    border-top-color:hsl(212, 86%, 64%);
  }
/* .works {
      width: 80%;
      margin: auto;
      margin-top: 10%;
      padding: 1rem;
      -webkit-column-count: 3;
      -webkit-column-gap: 0px;
      -moz-column-count: 3;
      -moz-column-gap: 0px;
      column-count: 3;
      column-gap: 10px;
    } */
@media only screen and (max-width: 600px){
  h1{
    font-size: 1.8rem;
  }
  .sub-head{
    width: 90%;
  }
  .team{
    margin-top: 11%;
  }
  .calculator{
    margin-bottom: 10%;
  }
}

</style>

