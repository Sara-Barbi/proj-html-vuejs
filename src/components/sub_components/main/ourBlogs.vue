<template>
  <div class="ourblogs">
    
    <div class="courses d-flex justify-content-center">
    
        <div v-for="(elementi, index) in arrayBlogs" :key="index" class="col-4 m-2">
          
            <div class="back">
              <img class="mb-2 myrad" :src="elementi.img" alt="">
              <div class="smallDiciture mb-3">{{elementi.artist}}</div>
              <div class="boldText mb-4 "> {{elementi.wtdo}}</div>
              
              <span class="smallDiciture mt-4 me-3"><i class="bi bi-calendar"></i>{{elementi.day}}</span>
              <span class="smallDiciture mt-4"><i class="bi bi-eye"></i>{{elementi.views}}</span>
            </div>   
        </div>

    </div>


  </div>
</template>

<script>
export default {
  name: 'ourBlogs',
  props: {
    arrayBlogs:Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../../../assets/style/variables.scss';
  .myrad{
    border-radius: 3px;
  }
  .back{
    background-color: #ececec;
  }
   
</style>
