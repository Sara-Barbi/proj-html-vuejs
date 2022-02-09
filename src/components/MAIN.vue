<template>
  <div class="main">
    <div class="firstBack">
    <workCulture/>
    <div class="containerr ">
      <div class="row text-center">
        <div class="col-12">
          <div class="smallDiciture">JOIN MAXCOACH AT BEST</div>
          <h2>Latest Online <h2 class="thinH2">Courses</h2></h2>
        </div>
        <courses :arrayCour='courses'/>

      </div>
    </div>
    </div>
    

    <ourBlogs/>

  </div>
</template>

<script>
import courses from './sub_components/main/courses.vue'
import ourBlogs from './sub_components/main/ourBlogs.vue'
import workCulture from './sub_components/main/workCulture.vue'



export default {
  name: 'MAIN',
  props: {
    
  },
  components:{
    courses,
    ourBlogs,
    workCulture
  },
  data(){
    return{
      courses:[
        {
          img: 'course-02-480x298.jpg',
          price:'$40.00',
          wtdo:'Learning toWrite as a Professional Author',
          nlessons:'20 Lessons',
          nstudents:'50 students',
          free: false,

        },
        {
          img: 'stock-full-hd-03-480x298.jpg',
          price:'$0.00',
          wtdo:'Customer-centric Info-Tech Strategies',
          nlessons:'23 Lessons',
          nstudents:'789 Students',
          free: "free",


        },
        {
          img: 'stock-full-hd-04-480x298.jpg',
          price:'$19.00',
          wtdo:'Open Programming Courses for Everyone: Python',
          nlessons:'17 Lessons',
          nstudents:'62 Courses',
          free: false

        },
        
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style  lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../assets/style/variables.scss';
  .firstBack{
    background-color: #e6e6e4;
  }
  .containerr{
    max-width: 1000px;
    margin: 0px auto;
    margin-top: 100px;
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
    .YTsimbol{
      width: 60px;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(64%, -20%);
      z-index: 2 ;
    }
  }
  .greenNumb{
    color: #2fab97;
    font-size: 30px;
    font-weight: bolder;

  }
  .smallDiciture{
   font-size: 12px;
   color: grey;
  }
  .thinH2{
    color: #2fab97;
    font-weight: 100;
    margin-bottom: 0;
  }
  

</style>
