<template>
     <div class="smallbox"> 
         <div class="lef">
              <div class="our">our service </div>
              <div> we have the best <br>
               export to call center <br>
                service</div>
         </div>
         <div class="rgi">
              using integration capabilities like APis, many disparate systems can be <br>
              combined to areate a best-in-breed ecosystem to better serve any particular <br>
              business function . with spicecCSM all manner of systems can be tied together
         </div>
         <hr>
         <div>
            <infinite-slide-bar :barStyle="{ background: '#FFF', padding: '5px 0'   }">
              <div style=" display: inline-block;" >
                   <h1 style="color:#49beb7;"> Dynamic call Support  </h1>
                   <div style="font-weight: bolder;"> to use an analgy that every <br> 
                   can relate to. our seasond team <br>
                   has seen the movie before. </div>
              </div>
            
            
              </infinite-slide-bar>
         </div>
    </div>
</template>

<script>
  
export default {
  name: 'boxservice'
}
</script>
 
<style scoped>
 .smallbox {
  margin: auto;
  width: 1100px;
  margin-top: 60px;
  padding-top: 175px;  
}
.smallbox .lef :first-child {  
   color: #ff5959;
  }
  .smallbox .lef   {
  font-weight: bolder;
    font-size: 50px;
    color: #49beb7;
     
    display: inline-block;
    width: 550px;
    
  }
  .smallbox .rgi {
      
    color: #000;
    font-size: 20px;
    margin-top: -190px;
    float: right;
  }
 hr {
   width: 1000px;
   color: #333;
 }
</style>
