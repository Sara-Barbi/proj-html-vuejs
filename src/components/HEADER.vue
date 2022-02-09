<template>
  <div class="header">
    <NAVbar 
        :arr='navArr'
        />
    <div class="container-fluid ">
      <div class="row">
        <div class="col-12 text-center d-flex flex-column justify-content-center align-items-center myBack">
          <h3>Commence Buisiness</h3>
          <h1>Distant Mentoring Program</h1>
          <button class="downloadGuide">Download free guidebook <i class="bi bi-arrow-right"></i></button>
        </div>
      </div>
    </div>
      
  </div>
</template>

<script>
import NAVbar from './sub_components/header/NAVbar.vue'


export default {
  name: 'HEADER',
  props: {
    
  },
  components:{
    NAVbar,
  },
  data(){
    return{
        navArr:[
          {
            Home:'Home',
          
            Pages:'Pages',
         
            Courses:'Courses',
          
            Features:'Features',
          
            Blog:'Blog',
         
            Shop:'Shop',
          }
        ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../assets/style/variables.scss';
  .myBack{
    background-image: $imgBack;
    background-size: $sizeBack;
    height: $backHeight;
    color: white;

  }
  .downloadGuide{
    width: 18%;
    background-color: white;
    font-size: 13px;
    font-weight: bold;
    color: rgb(27, 144, 105);
    padding: 10px 0;
    border: 0px;
    border-radius: 10px;
  }
  .downloadGuide:hover{
    width: 18%;
    background-color: rgb(27, 144, 105);
    font-size: 13px;
    font-weight: bold;
    color: rgb(255, 255, 255);
    padding: 10px 0;
    border: 0px;
    border-radius: 10px;
    transition: 1s ;
    
  }


</style>
