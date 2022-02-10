<template>
  <div class="">
    <div class="container">
      <div class="row caracterRow d-flex align-content-center ">

          <div v-for="(elem, index) in arr" :key='index' class="col-5 d-flex justify-content-around align-items-center">
              <div>{{elem.Home}}<i class="bi bi-chevron-down"></i></div>
              <div>{{elem.Pages}}<i class="bi bi-chevron-down"></i></div>
              <div>{{elem.Courses}}<i class="bi bi-chevron-down"></i></div>
              <div>{{elem.Features}}<i class="bi bi-chevron-down"></i></div>
              <div>{{elem.Blog}}<i class="bi bi-chevron-down"></i></div>
              <div>{{elem.Shop}}<i class="bi bi-chevron-down"></i></div>
          </div>
          <div class="col-2 d-flex align-items-center">
            <img src="../../../assets/image/dark-logo.png" alt="">
          </div>
          <div class="col-5 d-flex justify-content-end align-items-center">
            <i class="bi bi-cart me-3"> <div class="pallino">0</div> </i>
            <i class="bi bi-person-circle me-3"></i>
            <div class=' mySearch'>
              <input type="text"  placeholder="search..." aria-label="Recipient's username" aria-describedby="button-addon2">
              <i class="bi bi-search ii"></i>
            </div>

          </div>

       
      
      </div>
    </div>
  

  </div>
  
</template>

<script>



export default {
  name: 'NAVbar',
  props: {
    arr:Array,
    
  },
  components:{
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../../../assets/style/variables.scss';
  .container{
     min-height: $containerHeight;
     background-color: $backNav;
  }
  .caracterRow{
    min-height: $containerHeight;

  }
  img{
      width: 100%;
    }
 
  i{
    font-size: 15px;
    position: relative;
    .pallino{
      width: 10px;
      height:10px;
      font-size: 7px;
      font-weight: bold;
      line-height: 10px;
      vertical-align: middle;
      text-align: center;
      background-color: $celesteACQ;
      border-radius: 100%;
      position:absolute;
      color: white;
      top: 0px;
      right: -5px;
    }
  }
  .bi-chevron-down{
    font-size: 10px;
  }
  .mySearch{
    padding:7px;
    border-radius: 10px;
    background-color: $backsmoke;
    position: relative;
    input{
      border: 0px;
      background-color: $backsmoke;
      .ii{
        float: left;
        position: absolute;
        right: 20px;
        color: rgb(19, 187, 19);
      }
    }
  }
</style>
