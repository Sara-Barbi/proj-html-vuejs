<template>
  <div id="app">
    
    <HEADER/>
    <MAIN/>
    <FOOTER/>
  </div>
</template>

<script>
import HEADER from './components/HEADER.vue';
import  MAIN from './components/MAIN.vue';
import FOOTER from './components/FOOTER.vue';


export default {
  name: 'App',
  components: {
    HEADER,
    MAIN,
    FOOTER,

  },
/*
        {
          Address:'Address',
          addressInfo:{
              add:'382 NE st # 8734 Miami, FL 33179-3899',
              teleph:'+1(305)547-9909 (9am-5pm EST,Monday-Friday)',
              email:'support@maxcoach.com'

          }
        },
      ]
    }
  }
           */ 
}
</script>

<style lang="scss">
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
  @import './assets/style/global.scss';
  @import './assets/style/variables.scss';


</style>
