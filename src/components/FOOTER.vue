<template>
  <div class="footer">
    
    <newsLetter />
    <blueFooter :myFoot='infoFooter'/>


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
  },
  data(){
    return{
      infoFooter:[
         {
          locality:{
            title:'Address',
            coordinate:'328 NE 191st St #87394 Miami, FL 33179-23334',
            num: '+1(234)234-6553 (9am-5pm EST, Monday-Friday)',
            email:'support@maxcoach.com'
          },
          expl:{
            title:'Explore',
            start:'Start here',
            blog:'Blog',
            about:'About Us',
            success:'Success story',
            courses:'Courses',
            contact:'Contact Us'

          },
          information:{

          info:'Information',
          members:'Membership',
          guide:'Purchase guide',
          privacy:'Privacy policy',
          service:'Terms of service',
          },
 
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
