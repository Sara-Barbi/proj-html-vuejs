<template>
  <div class="footer">
    
    <newsLetter/>
    <blueFooter/>


  </div>
</template>

<script>

import newsLetter from './sub_components/footer/newsLetter.vue'
import blueFooter from './sub_components/footer/blueFooter.vue'

export default {
  name: 'FOOTER',
  props: {
    
  },
  components:{
    newsLetter,
    blueFooter
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../assets/style/variables.scss';
  

</style>
