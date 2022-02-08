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

</style>
