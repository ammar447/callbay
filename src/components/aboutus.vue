<template>
    <div class="cont">
      <img src="../assets/2.jpg" alt="test">
      <img  class="aa" src="../assets/1.jpg" alt="test">
      <div class="lef"> 
          <h5> about us</h5>
          <h1> We Help The Organizations <br>
               Create Databases    
           </h1>
           <div>
               <span> An experienced team management through forma processung servies. </span>
               <br>
               <span>We (Best call center) offerss the following forms processing services. </span>
               <br>
               <br>
               <br>
               Using integration capabilities like API’s, many disparate systems can <br>
                be combined to create a best-in-breed ecosystem to better serve any  <br>
                 particular business function. With SpiceCSM all manner of systems    <br>
             <div>
                 <h1>John Deo</h1>
                   chairman and founder 
                 <hr>
                   <img  src="../assets/signature.png" alt="test">  
                   
                       
             </div>
               
           </div>
      </div>
    </div>
</template>

<script>
export default {
    name : 'about us'
}
</script>

<style scoped>
.cont {
    width: 1300px;
   margin-top: 50px;
   
}
.cont img {
    float:right;
}
.cont .aa {
    position: absolute;
    top: 1585px;
    left: 730px;
} 
.cont .lef {
    padding-left: 110px ;
}
 .cont .lef h5 {
     color: #ff5959;
     font-size: 45px;
 }
.cont .lef h1 , span {
    color:  #49beb7;
    font-weight: bolder;
}
.cont .lef hr {
    height: 80px;
    width: 3px;
    background-color: black;
        margin-left: 205px;
    margin-top: -70px;
      
}
.cont .lef img {
    position: absolute;
    left: 400px;
    top: 1700px;
}
</style>