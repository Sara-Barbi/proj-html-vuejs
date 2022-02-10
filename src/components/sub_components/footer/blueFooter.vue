<template>
<div class="blueFooter">
    <div class="container-fluid myblueFooter">
        <div class="containerr">
            <div class="row myHFOOTER" >
                <div class="col-6">
                    <div v-for="(elementi,index) in myFoot" :key="index">
                        <div class="myTit">{{elementi.locality.title}}</div>
                        <ul>
                            <li>{{elementi.locality.coordinate}}</li>
                            <li>{{elementi.locality.num}}</li>
                            <li>{{elementi.locality.email}}</li>
                            
                        </ul>
                    </div>

                </div>
                <div class="col-4">
                         <div v-for="(elementi,index) in myFoot" :key="index">
                        <div class="myTit">{{elementi.expl.title}}</div>
                        <ul>
                            <li>{{elementi.expl.start}}</li>
                            <li>{{elementi.expl.blog}}</li>
                            <li>{{elementi.expl.about}}</li>
                            <li>{{elementi.expl.success}}</li>
                            <li>{{elementi.expl.courses}}</li>
                            <li>{{elementi.expl.contact}}</li>
                            
                        </ul>
                    </div>

                </div>
                <div class="col-2">
                         <div v-for="(elementi,index) in myFoot" :key="index">
                        <div class="myTit">{{elementi.information.info}}</div>
                        <ul>
                            <li>{{elementi.information.members}}</li>
                            <li>{{elementi.information.guide}}</li>
                            <li>{{elementi.information.privacy}}</li>
                            <li>{{elementi.information.service}}</li>
                            
                        </ul>
                    </div>

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

<style>
 

</style>