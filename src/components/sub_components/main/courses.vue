<template>
  <div class="courses d-flex justify-content-center">
  
      <div v-for="(elementi, index) in arrayCour" :key="index" class="col-4 m-3">
          
            <div class="back">
              <img class="mb-2" :src="elementi.img" alt="">
              <div class="greenPrice mb-3">{{elementi.price}}</div>
              <div class="boldText mb-4"> {{elementi.wtdo}}</div>
              <span class="smallDiciture me-3"><i class="bi bi-postcard"></i>{{elementi.nlessons}}</span>
              <span class="smallDiciture"><i class="bi bi-person"></i>{{elementi.nstudents}}</span>
            </div>   
      </div>


    

  </div>
</template>

<script>
export default {
  name: 'courses',
  props: {
    arrayCour:Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../../../assets/style/variables.scss';
  .back{
      background-color: white;
      min-height: 380px;
    img{
      width:95%;
      margin-top:10px;

    }
    .greenPrice{
    color: #2fab97;
    font-size: 20px;
    font-weight: bold;
    }
    .boldText{
      font-weight: bold;
      font-size: 18px;
    }

  }
  
</style>
