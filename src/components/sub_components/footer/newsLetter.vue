<template>
  <div class="newsletter">
    <div class="containerr mt-5 ">
      <div class="row text-center justify-content-center">
        <div class="col-6 mt-5">
          <h2 class=" fw-bolder" >Subscribe <h2 class="thinH2" style="display:inline-block">Newsletter</h2></h2>
          <div class="smallDiciture">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem obcaecati enim incidunt illo  Voluptatem obcaecati enim incidunt illo Voluptatem obcaecati enim incidunt illo  </div>
        </div>
      </div>
      <div class="row text-center justify-content-center">
        <div class=" col-6 mt-5 pt-5 mb-3">
          <input type="text" class="SubscribeInput" placeholder="Enter your email" >
          <span class="SubButton" >Subscribe</span>
        </div>
      </div>
      <img class="patterNews" src="../../../assets/image/maxcoach-shape-09.png" alt="">
      <img class="circleNews" src="../../../assets/image/maxcoach-shape-02.png" alt="">
    </div>

  </div>
</template>

<script>
export default {
  name: 'newsLetter',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../../../assets/style/variables.scss';
  .SubscribeInput{
    border: 0px;
    border-radius: 5px;
    font-size: 11px;
    background-color: $backsmoke;
    padding: 10px 115px 10px 25px;


  }
 .SubButton{
   font-size: 10px;
   font-weight: bold;
   padding: 12px 20px;
   background-color: $celesteACQ;
   border-radius: 0px 5px 5px 0px;
   color: white;
 }
 .SubButton:hover{
   font-size: 10px;
   font-weight: bold;
   padding: 12px 20px;
   background-color: #ffffff;
   border-radius: 0px 5px 5px 0px;
   color: $celesteACQ;
   border: 0.5px solid $smallDcolor;
   transition: 1s;
 }
 .patterNews{
   width: 170px;
   position: absolute;
   right: 20px;
   top: 10px;
 }
 .circleNews{
   position:absolute;
   width: 100px;
   bottom: 140px;
   right: 10px;
 }
 .containerr{
   max-height: 350px;
 }
</style>
