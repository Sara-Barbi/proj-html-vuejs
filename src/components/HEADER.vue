<template>
  <div class="header">
    <NAVbar 
        :arr='navArr'
        />
      
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
  

</style>
