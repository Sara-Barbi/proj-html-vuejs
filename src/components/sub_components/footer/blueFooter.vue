<template>
<div class="blueFooter">
    <div class="container-fluid myblueFooter mt-0 pt-0">
        <div class="containerr mt-0 myHFOOTER">
            <div class="row pt-5 " >
                <div class="col-6">
                    <div v-for="(elementi,index) in myFoot" :key="index">
                        <div class="myTit">{{elementi.locality.title}}</div>
                        <ul class="p-0 ">
                            <li class="smallDiciture mt-3">{{elementi.locality.coordinate}}</li>
                            <li class="smallDiciture mt-3">{{elementi.locality.num}}</li>
                            <li class="smallDiciture mt-3">{{elementi.locality.email}}</li>
                            <li class="pt-3"><i class="bi bi-facebook"></i><i class="bi bi-twitter"></i><i class="bi bi-instagram"></i><i class="bi bi-linkedin"></i></li>
                        </ul>
                    </div>

                </div>
                <div class="col-4 ">
                         <div v-for="(elementi,index) in myFoot" :key="index" class=" ">
                        <div class="myTit">{{elementi.expl.title}}</div>
                        <ul class="p-0 mymax d-flex flex-column flex-wrap">
                            <li class="smallDiciture mt-3">{{elementi.expl.start}}</li>
                            <li class="smallDiciture mt-3">{{elementi.expl.blog}}</li>
                            <li class="smallDiciture mt-3">{{elementi.expl.about}}</li>
                            <li class="smallDiciture mt-3">{{elementi.expl.success}}</li>
                            <li class="smallDiciture mt-3">{{elementi.expl.courses}}</li>
                            <li class="smallDiciture mt-3">{{elementi.expl.contact}}</li>
                            
                        </ul>
                    </div>

                </div>
                <div class="col-2">
                        <div v-for="(elementi,index) in myFoot" :key="index">
                        <div class="myTit">{{elementi.information.info}}</div>
                        <ul class="p-0">
                            <li class="smallDiciture mt-3">{{elementi.information.members}}</li>
                            <li class="smallDiciture mt-3">{{elementi.information.guide}}</li>
                            <li class="smallDiciture mt-3">{{elementi.information.privacy}}</li>
                            <li class="smallDiciture mt-3">{{elementi.information.service}}</li>
                            
                        </ul>
                    </div>

                </div>
            </div>
            <div class="row align-items-end mt-5 pt-5">
                <div class="col-12 text-center">
                    <div class="rights">© 2020 Maxcoach. All Rights Reserved</div>
                </div>
            </div>
        </div>
    </div>

</div>
  
</template>

<script>
export default {
  name:'blueFooter',
  props:{
      myFoot:Array

  }
}

 
</script>

<style lang="scss" scoped>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.0/font/bootstrap-icons.css"); 
@import '../../../assets/style/variables.scss';
.myblueFooter{
    background-color: rgb(15, 15, 23) ;
    
}
.myTit{
    color: white;
    font-size: 15px;
}
ul{
    li{
        list-style-type: none;
        i{
             
        width: 25px;
        color: $smallDcolor;
        margin-right: 20px;
        
   
        }

    }
}
.smallDiciture:hover{
    color: white;
}
.mymax{
    max-height: 130px;
}
.myHFOOTER{
    max-height: 350px;
}
.rights{
    font-size: 10px;
    color: $smallDcolor;
}

</style>