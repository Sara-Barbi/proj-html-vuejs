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
                        <div class="myTit">{{elementi.locality.title}}</div>
                        <ul>
                            <li>{{elementi.locality.coordinate}}</li>
                            <li>{{elementi.locality.num}}</li>
                            <li>{{elementi.locality.email}}</li>
                            
                        </ul>
                    </div>

                </div>
                <div class="col-2">
                         <div v-for="(elementi,index) in myFoot" :key="index">
                        <div class="myTit">{{elementi.locality.title}}</div>
                        <ul>
                            <li>{{elementi.locality.coordinate}}</li>
                            <li>{{elementi.locality.num}}</li>
                            <li>{{elementi.locality.email}}</li>
                            
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