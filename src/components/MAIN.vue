<template>
  <div class="main">
    <div class="containerr">
      <div class="row mt-5 justify-content-center">
        <div class="col-5  ps-5 ">
          <p>EVERYTHING IN MAXCOACH</p>
          <h2>Learn about our <h2 class="thinH2">Work Culture</h2>at maxCoach</h2>
          <p>Spend some time to visit our website ar head office and discover our current courses, enrollmen procedure,and regustration deadline. Were opening new classes every beginning of each month.</p>
          <p>Have questions?get Free Guide</p>
        </div>
        <div class="col-5">
          <img class='imgPrinc' src="../assets/image/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
          <img class='imgTop' src="../assets/image/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
          <img class='pattern' src="../assets/image/maxcoach-shape-07-100x100.png" alt="">
          <img class='circle' src="../assets/image/maxcoach-shape-02.png" alt="">

        </div>
      </div>
      <div class="row mt-5">

        <div class="col-5">
          <img class='imgYou' src="../assets/image/stock-full-hd-11-670x450.jpg" alt="">
          <img src="../assets/image/maxcoach-shape-05-150x150.png" alt="" class='romboPoints'>
          <img src="../assets/image/svg-0.svg" alt="" class='svgIMG'>
          <img class='patternPoints' src="../assets/image/maxcoach-shape-07-100x100.png" alt="">
          

        </div>
        <div class="col-5  ps-5 ">
          <p>EVERYTHING IN MAXCOACH</p>
          <h2>Learn about our <h2 class="thinH2">Work Culture</h2>at maxCoach</h2>
          <p>Spend some time to visit our website ar head office and discover our current courses, enrollmen procedure,and regustration deadline. Were opening new classes every beginning of each month.</p>
          <p>Have questions?get Free Guide</p>
        </div>
      </div>
    </div>

    <courses/>

    <ourBlogs/>

  </div>
</template>

<script>
import courses from './sub_components/main/courses.vue'
import ourBlogs from './sub_components/main/ourBlogs.vue'


export default {
  name: 'MAIN',
  props: {
    
  },
  components:{
    courses,
    ourBlogs
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../assets/style/variables.scss';
  
  .containerr{
    max-width: 1200px;
    margin: 0 auto;
  }

  div{
    
    position: relative;
    .imgPrinc{
      width: 300px;
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
      width: 350px;
      top: 40px;
      right: 10px;
      z-index: 1;
    }
    .svgIMG{
      position: absolute;
      width: 50px;
      top: 10px ;
      right: 330px ;
      filter: brightness(50%);

    }
    .romboPoints{
      position: absolute;
      width: 70px;
      top: 45px;
      right: 340px;

    }
    .patternPoints{
       position: absolute;
       width: 70px;
       bottom: -10px;
       right: 0;
    }
  }
  

</style>
