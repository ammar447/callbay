<template>
    <div class="cont" >
            <h4>RECENT POSTS</h4>
            <h1>Latest News & Blog</h1>
       <div class="lef" >
            <img src="../assets/4.jpg" alt="">
            <div>
                <h1>The Call Center School <br>
                 Launches Free Course</h1>
                 Bring to the table win-win survival <br>
                  strategies to ensure proactive <br>
                   domination. At the end of the day, going .....
                   <hr>
            </div>
       </div>
       <div class="lef" >
              <img src="../assets/5.jpg" alt="">
                    <div>
                <h1>The biggest challenges <br>
                for call  centers faces</h1>
                 Bring to the table win-win survival <br>
                  strategies to ensure proactive <br>
                   domination. At the end of the day, going .....
                   <hr>
            </div>
       </div >
       <div class="lef" >
             <img src="../assets/6.jpg" alt="">
            <div>
                <h1>How to Quickly deploy <br>
                strategic networks.</h1>
                 Bring to the table win-win survival <br>
                  strategies to ensure proactive <br>
                   domination. At the end of the day, going .....
                   <hr>
            </div>
       </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.cont {
     width: 100%;
    margin-top: 100px;
          height: 675px;
    background-color: #f5f5f5;
}
.cont h4 {
    color: #ff5959 ;
        text-align: center;
            padding-top: 35px;
}
.cont h1 {
     color:  #49beb7;
         text-align: center;
}
.cont .lef {
      float: left;
    margin-left: 60px;
    margin-top: 40px;
    padding: 22px;
    background-color: #FFF;
}
.cont .lef img {
       width: 320px;
}
.cont .lef img:hover{
    perspective: 600px;
     transform: scale(1.09);
         transition: all 0.3s ease-out 0.3s;
     
}
.cont .lef h1 {
    color:  #49beb7;
}
.cont .lef h1:hover {
    color:  #ff5959;
     cursor: pointer
}
.cont .lef div {
    line-height: 1.5;
}
</style>