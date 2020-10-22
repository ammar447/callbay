<template>
    <div class="cont1" >  
         <div class="lef1" >
             <img src="../assets/whitelogo.png" alt="test"> 
             <br>
             We work to ensure people’s com fort at <br> 
             their company specializing in house. <br>
             <span>123-456-78910</span>
             <br>
             <button>REQUEST WITH ONLINE FORM</button>
         </div>
         <div class="lef1">
              <h2>Useful Links</h2>
                 <hr>  
              <ul>
                  <li><a href="#"> <router-link to="/">Home</router-link>  </a></li>
                   <li><a href=""> <router-link to="/About">About</router-link> </a> </li>
                    <li><a href=""> <router-link to="/Coreteam">Coreteam</router-link></a></li>
                     <li>Consulting</li>
                      <li>Power Dialer</li>
              </ul>
         </div>
         <div class="lef1">
               <h2>About Callbay</h2>
                <hr> 
                  <br>
               Tamplate monster HQ <br>
               24 Fifth st., Los Angeles, USA <br>
               <hr>
               <br>
                ammar.hariri321@gmail.com <br>
                <hr>
                <br>
                Phone : +12 (3) 456 0000 <br>
                 Support : +12 (3) 456 0000
         </div>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.cont1 {
    width: 100%;
       height: 335px;
    background-image: url("../assets/end.jpg");
}
.cont1 .lef1 {
    float: left;
    color: #FFF;
    margin-left: 150px;
    margin-top:15px;
        line-height: 1.7;
        
}
.cont1 .lef1 img {
      width: 300px;
}
.cont1 .lef1 span {
     color: #ff5959 ;
     font-size: 40px;
}
.cont1 .lef1 button {
     border-radius: 0px;
     font-size: 15px;
    padding: 15px 20px;
    font-weight: 600;
    background: none;
    color: #FFF;
    cursor: pointer;
    border: 2px solid #FFF;
}
.cont1 .lef1 button:hover {
     color:  #49beb7 ;
   background-color: #FFF;
}
.cont1 .lef1 ul li {
     margin-left: -40px;
    line-height: 2.1;
    list-style: none;
     text-decoration: none;
}
.cont1 .lef1  ul li a
{
    color:#FFF; text-decoration: none;
}
.cont1 .lef1 ul li:hover {
     color: #ff5959 ;
     cursor: pointer;
}
.cont1 .lef1  hr  {
     display: inline-block;
   background-color:#ff5959 ;
       border: 0;
      width: 110px;
    height: 2px;   
}
</style>