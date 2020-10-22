<template>
    <div class="cont" >
        <div >
             <div class="onb">
            <img src="../../assets/21.jpg" alt="">
            <div class="handsp" >
                <h3>Barbra J. Zambrano</h3>
               <span>CFO</span>
            </div>
            
        </div>
         <div class="onb">
             <img src="../../assets/22.jpg" alt="">
             <div class="handsp" >
                <h3>Roger M. Howell</h3>
               <span>CEO</span>
            </div>
         </div>
          <div class="onb">
            <img src="../../assets/23.jpg" alt="">
            <div class="handsp" >
                <h3>Joyce V. Garcia</h3>
               <span>District Manager</span>
            </div>
          </div>
           <div class="onb">
            <img src="../../assets/24.jpg" alt="">
            <div class="handsp" >
                <h3>Jacob B. McGinley</h3>
               <span>Genaral Manager</span>
            </div>
             
           </div>
            <div class="onb">
                 <img src="../../assets/25.jpg" alt="">
                 <div class="handsp" >
                <h3>Timothy D. Hall</h3>
               <span>Team Manager</span>
                </div>
            </div>
             <div class="onb">
                <img src="../../assets/26.jpg" alt="">
                 <div class="handsp" >
                 <h3>Audrey S. Cook</h3>
                 <span>Business Developer</span>
                 </div>
             </div>
        </div>   
    </div>
</template>

<script>
export default {
    name: 'team'
}
</script>

<style scoped>
.cont {
    width: 1200px;
    height: 1355px;
}
.cont .onb {
    margin-top: 150px;
    margin-left: 50px;
    float: left;
    display: block;
}
.cont .onb img {
        width: 350px;
}
.cont .onb .handsp {
    background-color: #49beb7;
    text-align: center;
    padding: 8px;
    margin-top: -20px;
    font-weight: 700;
    color: #FFF;
    font-size: 26px;
    border-bottom:4px solid #ff5959 ;
}
.cont .onb .handsp span {
   color:#ff5959; 
    font-size: 20px;
}
</style>