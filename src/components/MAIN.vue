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

        <div class="row justify-content-center">
          <div class="col-12 text-center">
            <div class="dots d-flex align-content-center justify-content-center"><i class="bi bi-dot bigSize"></i><i class="bi bi-dot"></i><i class="bi bi-dot"></i><i class="bi bi-dot"></i><i class="bi bi-dot"></i></div>

          </div>
          <div class="col-5 text-center">
            <div class="smallDiciture">Controll your personal preference settings to get notified about appropriate courses. <div class="view">View all courses  <i class="view bi-arrow-right"></i></div></div>

          </div>
        </div>


      </div>
    </div>
    </div>

    <HeartUs/>
    

    <ourBlogs/>

  </div>
</template>

<script>
import courses from './sub_components/main/courses.vue'
import ourBlogs from './sub_components/main/ourBlogs.vue'
import workCulture from './sub_components/main/workCulture.vue'
import HeartUs from './sub_components/main/HeartUs.vue'




export default {
  name: 'MAIN',
  props: {
    
  },
  components:{
    courses,
    ourBlogs,
    workCulture,
    HeartUs
  },
  data(){
    return{
      courses:[
        {
          img: require('../assets/image/course-02-480x298.jpg'),
          price:'$40.00',
          wtdo:'Learning toWrite as a Professional Author',
          nlessons:'20 Lessons',
          nstudents:'50 students',
          free: false,

        },
        {
          img: require('../assets/image/stock-full-hd-03-480x298.jpg'),
          price:'$0.00',
          wtdo:'Customer-centric Info-Tech Strategies',
          nlessons:'23 Lessons',
          nstudents:'789 Students',
          free: "free",


        },
        {
          img: require('../assets/image/stock-full-hd-04-480x298.jpg'),
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
  .view{
    color: black;
    font-weight: bold;
    font-size: 12px;
  }
  .containerr{
    max-width: 1000px;
    margin: 0px auto;
    margin-top: 100px;
  }
  .bi-dot{
    line-height: 40px;
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
