<template>
    <div class="containerr1">
      <div class="row  justify-content-center ">
        <div class="col-4 pt-5 mt-5 ps-5 ">
          <p class='smallDiciture'>EVERYTHING IN MAXCOACH</p>
          <h2>Learn about our <h2 class="thinH2">Work Culture</h2>at maxCoach</h2>
          <p class='smallDiciture'>Spend some time to visit our website ar head office and discover our current courses, enrollmen procedure,and regustration deadline. Were opening new classes every beginning of each month.</p>
          <span class='smallDiciture view ' >Have questions? <span style="color:#2fab97;">Get Free Guide <i class="view bi-arrow-right"></i></span></span>
        </div>
        <div class="col-8 mypa mt-5">
          <img class='imgPrinc' src="../../../assets/image/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
          <img class='imgTop' src="../../../assets/image/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
          <img class='pattern' src="../../../assets/image/maxcoach-shape-07-100x100.png" alt="">
          <img class='circle' src="../../../assets/image/maxcoach-shape-02.png" alt="">

        </div>
      </div>
      
      <div class="row justify-content-center mt-5 mb-5">
        <div class="col-3 d-flex flex-column align-items-center"><div class="greenNumb">129+</div><div class='smallDiciture'>ENROLLED LEANERS</div></div>
        <div class="col-3 d-flex flex-column align-items-center"> <div class="greenNumb">80</div><div class='smallDiciture'>FINISHED SESSIONS</div></div>
        <div class="col-3 d-flex flex-column align-items-center"> <div class="greenNumb">4%</div> <div class='smallDiciture'>SATISFACTION RATE</div> </div>
      </div>


      <div class="row ">

        <div class="col-8 mt-5">
          <img class='imgYou' src="../../../assets/image/stock-full-hd-11-670x450.jpg" alt="">
          <img class="YTsimbol" src="../../../assets/image/icon-youtube-play.png" alt="">
          <img src="../../../assets/image/maxcoach-shape-05-150x150.png" alt="" class='romboPoints'>
          <img src="../../../assets/image/svg-0.svg" alt="" class='svgIMG'>
          <img class='patternPoints' src="../../../assets/image/maxcoach-shape-07-100x100.png" alt="">
          

        </div>
        <div class="col-4 pt-5   mt-5">
          <p class='smallDiciture'>EVERYTHING IN MAXCOACH</p>
          <h2>Learn about our <h2 class="thinH2">Work Culture</h2>at maxCoach</h2>
          <p class='smallDiciture'>Spend some time to visit our website ar head office and discover our current courses, enrollmen procedure,and regustration deadline. Were opening new classes every beginning of each month.</p>
          <span class='smallDiciture view ' >Have questions? <span style="color:#2fab97;">Get Free Guide <i class="view bi-arrow-right"></i></span></span>
          
        </div>
      </div>
    </div>

</template>

<script>
export default {
    name:'workCulture'

}
</script>

<style lang="scss">
 @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
 @import '../../../assets/style/variables.scss';
.bigSize{
    font-size: 40px;
    margin-right: -10px;
  }

  .mypa{
    
    position: relative;
    height: 400px;
    
    .imgPrinc{
      width: 470px;
      position: relative;
      top: 50px;
      right: -40px;
      margin: auto 0;
      z-index: 1;

    }
    .imgTop{
      position: absolute;
      width: 80px;
      top: 20px;
      z-index: 2;
    

    }
    .pattern{
      position: absolute;
      top: 26px;
      right: 150px;
      width: 78px;

    }
    .circle{
      width:70px;
      position: absolute;
      z-index: 3;
      bottom: 30px;
      right: 200px;

    }
  }
  div{
    position: relative;
    .imgYou{
      position: absolute;
      width: 470px;
      top: 40px;
      left: 10px;
      z-index: 1;
    }
    .svgIMG{
      position: absolute;
      width: 100px;
      top: -10px ;
      left: -50px;
      

    }
    .romboPoints{
      position: absolute;
      width: 110px;
      top: 60px;
      left: -80px;

    }
    .patternPoints{
       position: absolute;
       width: 100px;
       bottom: -100px;
       right: 180px;
    }
    .YTsimbol{
      width: 60px;
      position: absolute;
      top: 180px;
      left: 170px;
      transform: translate(64%, -20%);
      z-index: 2 ;
    }
  }
  .containerr1{
 
    max-width: 1000px;
    margin: 0px auto;
    margin-top: 0px;
    margin-bottom: 150px;

  }
</style>