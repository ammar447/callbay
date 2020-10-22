<template>
    <div class="cont">
      <img src="../../assets/2.jpg" alt="test">
      
      <div class="lef"> 
          <h5> about us</h5>
          <h1>We are a leading client call <br>
              service provider, clients and <br>
              worldwide   
           </h1>
           <div>
                
               <span> Get help from a caring and knowledgeable professional. Let us </span>
               <br>
               <span>know what we can do to make your life easier. </span>
               <br>
               <br>
               <br>
              There are many variations of passages of Lorem Ipsum <br>
                available, but the majority have suffered alteration in some <br>
                form, by injected humour, or randomised words which don’t   <br>
                look even slightly believable. If you are going to use a passage <br>
                of Lorem Ipsum, you need to be sure there isn’t anything <br>
                embarrassing <br>
                25 years of experience <br>
             <div>
                 <br>
                 <img class="call" src="../../assets/icon/call1.png" alt="">
                 <h2> OUR PROJECT </h2>   
                   
                       
             </div>
               
           </div>
      </div>
    </div>
</template>

<script>
export default {
    name : 'aboutin'
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
.cont .lef h2 {
    padding-left: 108px;
    cursor: pointer;
     color:  #49beb7;
}

.cont .lef .call {
     float: left;
 }
 
</style>