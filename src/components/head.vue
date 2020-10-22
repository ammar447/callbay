<template>
    <div class="contiener">

    <div class="slider">    
         <img src="../assets/icon/100.png" alt="test">
           <img src="../assets/icon/101.png" alt="test">
          <img src="../assets/icon/102.png" alt="test">
           <ul>
                    <li class="z"><router-link to="/">HOME</router-link></li>
                    <li><a href="#"> <router-link to="/About">About</router-link>  </a></li>
                      <li><a href="#"> <router-link to="/Coreteam">Coreteam</router-link></a></li>
                    <li><a href="#">services</a></li>
                    <li><a href="#">blog & news</a></li>
                    <li><a href="#">reach-out</a></li>
            </ul>    
    </div> 
          
    </div>
</template>

<script>
export default {
   name : 'head', 
}
</script>

<style scoped>
.contiener {
  /*background-color: aquamarine; */
   width: 100%; 
   height: 60px;
   text-align: center;
   margin: auto;
   padding: 7px;
   background-color: #49beb7;
 }
 .slider {
      position: absolute;
    right: 13%;
    padding-left: 85px;
 }
 .contiener .slider img {
        width: 20px;
    float: left;
    margin-left: 24px;
    margin-top: 22px;
     cursor: pointer;

 }
 
 .slider  ul
{
   list-style: none;
     
    padding-left: 0px;
    display: block;
        margin-left: 355px;
   
    
}
.slider ul li 
{
    float: left;
    padding-right: 25px;
    margin: 7px;
    text-transform: uppercase;
    font-weight: bolder;
}
 .slider  ul li a
{
    color:#FFF; text-decoration: none;
}
  .slider  ul li a:hover{
    color:#ff5959;
}

</style>