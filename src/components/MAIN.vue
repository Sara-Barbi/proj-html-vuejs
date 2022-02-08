<template>
  <div class="main">

    <courses/>

    <ourBlogs/>

  </div>
</template>

<script>
import courses from './sub_components/main/courses.vue'
import ourBlogs from './sub_components/main/ourBlogs.vue'


export default {
  name: 'MAIN',
  props: {
    
  },
  components:{
    courses,
    ourBlogs
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import '../assets/style/variables.scss';
  

</style>
