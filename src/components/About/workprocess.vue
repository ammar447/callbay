<template>
 <div class="cont">
       <div class="first">
           <h5>WORK PROCESS</h5>
           <h1>Our Seamless Process</h1>
       </div>
       <div>
           
           <div  class="lef1">
               <span> 
                   <span class="on">01</span>  <hr>
                     <h4> Inquiry</h4>
                   <div class="toww">
                   
                  It is a long established fact that a
                   <br> reader will be distracted by the
                   <br> readable content.
            

                   </div>
                
               </span>
           
           </div>
           <div  class="lef1">
               <span> 
                   <span class="on">02</span>  <hr>
                        <h4>Project Assessment </h4>
                   <div class="toww">
                   
                  The point of using Lorem Ipsum is
                   <br> that it has a more-or-less normal
                   <br> distribution.
            

                   </div>
                
               </span>
           
           </div>
           <div  class="lef1">
               <span> 
                   <span class="on">03</span>  <hr>
                     <h4> Project Execution </h4>
                   <div class="toww">
                   
                    Many desktop publishing packages
                   <br> and web page editors now use
                   <br>Lorem Ipsum.
            

                   </div>
                
               </span>
           
           </div>
               
       </div>
  </div>    
</template>

<script>
export default {
    name : 'workprocess'
}
</script>

<style scoped>
.cont {
    width: 100%;
    margin-top: 100px;
    padding-top: 15px;
    background-color: #f5f5f5; 
}
.cont .first {
    text-align: center;
}
.cont .first h5 {
    color: #ff5959 ;
}
.cont .first h1 {
    color:  #49beb7 ;
        font-size: 50px;
}
.cont .lef1 {
    display: inline-block;
    padding-bottom: 50px;
    margin-left: 40px;
    margin-top: 35px;
    font-size: 35px;
    line-height: 1.5;
    color: #49beb7;
}
.cont .lef1 h4
{ 
    display: inline;
        padding-left: 60px;
}
.cont .lef1 .on {
   color: #FFF;
    background-color: #ff5959;
    padding: 3px;
    font-size: 25px;
}
  
.cont .lef1 hr {
    display: inline-block;
    width: 50px;
    height: 1px;
    position: absolute;
    top: 1400px;
    background-color: #ff5959;
}
.cont .lef1  .toww {
    line-height: 1.2;
    font-size: 25px;
    margin-top: 45px;
    margin-left: 53px;
    color: black;
}
</style>