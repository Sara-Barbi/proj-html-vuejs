<template>
<div class="containerr">
    <div class="row">
        <div class="col-6">
          <p class='smallDiciture'>EVERYTHING IN MAXCOACH</p>
          <h2>Why Do People <h2 class="thinH2">*Hearts*</h2>Us?</h2>
          <p class='smallDiciture'>Spend some time to visit our website ar head office and discover our current courses, enrollmen procedure,and regustration deadline. Were opening new classes every beginning of each month.</p>
          <p class='view'>view of <i class="view bi-arrow-right"></i></p>
        </div>
        <div class="col-6">
            <div  class="userCard">
              
              

                <div @click="userHeart[0].current==true ? userHeart[0].current=false : userHeart[0].current=true "  :class="userHeart[0].current==true ?'active' : 'unActivetop' "    >
                    <div class="formUser m-2">{{userHeart[0].title}}</div>
                    <div class="smallDiciture m-3">{{userHeart[0].request}}</div>
                    <div class="d-flex m-3">
                        <img class="piccoloUser " :src='userHeart[0].img' alt="">
                        <div >
                            <div class="formUser">{{userHeart[0].name}}</div>
                            <div class="smallDiciture">{{userHeart[0].profe}}</div>
                        </div>
                    </div>
                    <div class="d-none">{{userHeart[0].current}}</div>    
                
                </div>
                <div   :class="userHeart[1].current==true ?'active' : 'unActive' " class="userCard"  @click="userHeart[1].current==false ? userHeart[1].current=true : userHeart[1].current=false" >
                    <div class="formUser m-2">{{userHeart[1].title}}</div>
                    <div class="smallDiciture m-3">{{userHeart[1].request}}</div>
                    <div class="d-flex m-3">
                        <img class="piccoloUser " :src='userHeart[1].img' alt="">
                        <div >
                            <div class="formUser">{{userHeart[1].name}}</div>
                            <div class="smallDiciture">{{userHeart[1].profe}}</div>
                        </div>
                    </div>
                    <div class="d-none">{{userHeart[1].current}}</div>    
                
                </div>
                <div   :class="userHeart[2].current==true ?'active' : 'unActivetop' " class="userCard"  @click="userHeart[2].current==false ? userHeart[2].current=true : userHeart[2].current=false" >
                    <div class="formUser m-2">{{userHeart[2].title}}</div>
                    <div class="smallDiciture m-3">{{userHeart[2].request}}</div>
                    <div class="d-flex m-3">
                        <img class="piccoloUser " :src='userHeart[2].img' alt="">
                        <div >
                            <div class="formUser">{{userHeart[2].name}}</div>
                            <div class="smallDiciture">{{userHeart[2].profe}}</div>
                        </div>
                    </div>
                    <div class="d-none">{{userHeart[2].current}}</div>    
                
                </div>
              
            </div>
        </div>
        
    </div>
    <div class="row myT">
        <div class="col-7 ">

            <img class='teamIMG' src="../../../assets/image/home-3-team-image.png" alt="">
            <img class="puntodiPunti" src="../../../assets/image/maxcoach-shape-05-100x100.png" alt="">
            <img class="iSVG" src="../../../assets/image/svg-0.svg" alt="">
            <img class='linee' src="../../../assets/image/maxcoach-shape-07-100x100.png" alt="">
            <img class="quadratodiPunti" src="../../../assets/image/maxcoach-shape-01.png" alt="">

        </div>
        <div class="col-5">
            <p class='smallDiciture'>EVERYTHING IN MAXCOACH</p>
            <h2>We're Here To <h2 class="thinH2">Transform</h2>You</h2>
            <p class='smallDiciture'>Spend some time to visit our website ar head office and discover our current courses, enrollmen procedure,and regustration deadline. Were opening new classes every beginning of each month.and regustration deadline. Were opening new classes every beginningand regustration deadline. Were opening new classes every beginning</p>
            <button class="greenB">Get Free Guide</button>


        </div>
    </div>
    
</div>
  
</template>

<script>
export default {
  name:'HeartUs',
  data(){
      return{
         
          userHeart:[
              {
                  title:'professional team of specialists and appassionate mentors at reah',
                  request:'I need to get a certification for English courses and MaxCoach is my best choice. their improved fast and tutor are the best teachers i have ever seen!',
                  img: require('../../../assets/image/testimonial-avata-01.jpg'),
                  name:'MADLEY PONDOR',
                  profe:'/IT specialist',
                  current:true,

              },
              {
                  title:'professional team of specialists and appassionate mentors at reah',
                  request:'I need to get a certification for English courses and MaxCoach is my best choice. their improved fast and tutor are the best teachers i have ever seen!I need to get a certification for English courses and MaxCoach is my best choice. their improved fast and tutor are the best teachers i have ever seen!I need to get a certification for English courses and MaxCoach is my best choice. their improved fast and tutor are the best teachers i have ever seen!',
                  img:require('../../../assets/image/testimonial-avata-02.jpg'),
                  name:'MINA HOLLACE',
                  profe:'/FreeLancer',
                  current:false
              },
              {
                  title:'professional team of specialists and appassionate mentors at reach. Tutors policy',
                  request:'I need to get a certification for English courses and MaxCoach is my best choice. their improved fast and tutor are the best teachers i have ever seen!',
                  img:require('../../../assets/image/testimonial-avata-03.jpg'),
                  name:'MASSIMO BARBI',
                  profe:'/Freelancer',
                  current:false
              },
              
          
          ]
      }
  },
  methods:{
      
  }
}

</script>

<style lang="scss">
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
.piccoloUser{
    width: 40px;
    height: 40px;
    border-radius: 100%;
}
.formUser{
    font-size: 14px;
    font-weight: bold;
}


.active{
    background-color: rgb(255, 255, 255);
    z-index: 1;
    min-height: 210px;
    top: 0 ;
    left: 0;
    
    box-shadow: 2px 2px 2px 2px #bfbdbd ;
    
    

}
.userCard{
    min-height: 210px;
    position: absolute;
    width: 100%;
}

.unActive{
    
    top: 80px;
    right: -30px;
    filter: opacity(40%);
    
    background-color:rgb(255, 255, 255);
}
.unActivetop{
    
    top: -50px;
    right: -30px;
    filter: opacity(40%);
    
    background-color:rgb(255, 255, 255);
}

.myT{
    margin-top: 8rem !important;
    .teamIMG{
        width: 350px;
        position: relative;
        left: 0px;
        z-index: 1;
    }
    .puntodiPunti{
        position: absolute;
        top: 70px;
        left: -60px;
    }
    .iSVG{
        width: 100px;
        position: absolute;
        top: 10px;
        left: 5px;
    }
    .linee{
        position: absolute;
        width: 90px;
        bottom: -70px;
        right: 350px;
        
    }
    .quadratodiPunti{
        position: absolute;
        width: 100px;
        bottom: 0;
        left: -190px;
        
        
    }
}
.greenB{
    padding: 10px 30px;
    color: white;
    font-size: 12px;
    font-weight: bold;
    background-color: #1fad95;
    border: 0px;
    border-radius: 5px;
}

</style>