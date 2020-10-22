<template>
      <div class="contiener">
       <img class="logo" alt="call logo" src="../assets/logo.png" />
        <p> 
          <span> <img src="../assets/icon/call1.png" alt="call"> </span> (123) 4567 89-10 
          <span><img src="../assets/icon/email1.png" alt="call"> </span> ammar.hariri321@gmail.com 
          <span><img src="../assets/icon/loc.png" alt="call"></span> new york 
        </p>
    </div>
</template>

<script>
export default {
  name: "first",
  
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  *
{ 
 box-sizing: border-box;
  
}
 .contiener {
  /*background-color: aquamarine; */
   width: 1140px; 
   height: 75px;
   text-align: center;
   margin: auto;
 } 
 .contiener .logo {
   float: left;
    height: 70px;
     width: 250px; 
 }
 .contiener p {
    cursor: pointer
 }
 .contiener p span {
  /* padding: 5px; */
  padding: 20px;
  
 }
</style>
