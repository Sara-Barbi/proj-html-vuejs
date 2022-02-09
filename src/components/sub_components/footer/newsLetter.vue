<template>
  <div class="newsletter">
    <div class="containerr mt-5 ">
      <div class="row text-center justify-content-center">
        <div class="col-6 mt-5">
          <h2>Subscribe <h2 class="thinH2" style="display:inline-block">Newsletter</h2></h2>
          <div class="smallDiciture">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem obcaecati enim incidunt illo  Voluptatem obcaecati enim incidunt illo Voluptatem obcaecati enim incidunt illo  </div>
        </div>
      </div>
      <div class="row text-center justify-content-center">
        <div class=" col-6 mt-5 pt-5 mb-3">
          <input type="text" class="SubscribeInput" placeholder="Enter your email" >
          <span class="SubButton" >Subscribe</span>
        </div>
      </div>
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
    background-color: #ececec;
    padding: 10px 115px 10px 25px;


  }
 .SubButton{
   font-size: 10px;
   font-weight: bold;
   padding: 12px 20px;
   background-color: #1fad95;
   border-radius: 0px 5px 5px 0px;
   color: white;
 }
</style>
