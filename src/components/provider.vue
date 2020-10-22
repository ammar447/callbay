<template>
  <div >
    <div class="contiener">
        <transition-group name="fade" tag="div">
      <div v-for="i in [currentIndex]" :key="i">
        <img :src="currentImg" />
      </div>
    </transition-group>
    <a class="prev" @click="prev" href="#">&#10094; Previous</a>
    <a class="next" @click="next" href="#">&#10095; Next</a>
    </div>
    <div class="learnmore">
        <div class="our"> OUR SERVICES</div>
        <p> Call Center Sales & CEM   </p>
        <p> <span> Everything is </span> Recorded </p>
        <div  >we are a leading client call service provider </div>
        <button> Leran More </button>
    </div>
  
  </div>
</template>
<script>
export default {
  name: "Slider",
  data() {
    return {
      images: [
        "https://cdn.shortpixel.ai/client/q_glossy,ret_img,w_1920,h_1079/http://primehostingindia.com/templatemonster/wp/callbay/wp-content/uploads/2020/09/HP1-S03.jpg",
        "https://cdn.shortpixel.ai/client/q_glossy,ret_img,w_1920,h_1079/http://primehostingindia.com/templatemonster/wp/callbay/wp-content/uploads/2020/09/HP.1-1.jpg",
     
      ],
      timer: null,
      currentIndex: 0
    };
  },

  mounted: function() {
    this.startSlide();
  },

  methods: {
    startSlide: function() {
      this.timer = setInterval(this.next, 20000);
    },

    next: function() {
      this.currentIndex += 1;
    },
    prev: function() {
      this.currentIndex -= 1;
    }
  },

  computed: {
    currentImg: function() {
      return this.images[Math.abs(this.currentIndex) % this.images.length];
    }
  }
};
</script>
<style scoped>
 .contiener {
     width: 100%;
 }
 .learnmore {
      display: inherit;
    width: 80%;
    margin-top: -520px;
    margin-left: 164px;
    
     
 }
 .learnmore div {
   color: #FFF;
   font-weight: bolder;
 }
 .learnmore .our {
   font-weight: bolder ;
    color : #49beb7
 }
 .learnmore p {
    color: #FFF;
    line-height: 30px;
    font-size: 55px;
    font-weight: bolder
 }
 .learnmore p span {
   color: #ff5959;
 }
 button {
    color: #FFF;
    background: #ff5959;
    padding: 16px;
    margin-top: 30px;
    font-weight: 900;
     cursor: pointer
 }
.fade-enter-active,
.fade-leave-active {
  transition: all 0.9s ease;
  overflow: hidden;
  visibility: visible;
  position: absolute;
  width:100%;
  opacity: 1;
}

.fade-enter,
.fade-leave-to {
  visibility: hidden;
  width:100%;
  opacity: 0;
}

img {
  height:600px;
  width:100%
}

.prev, .next {
  cursor: pointer;
  position: absolute;
      top: 110%;
  width: auto;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.7s ease;
  border-radius: 0 4px 4px 0;
  text-decoration: none;
  user-select: none;
}

.next {
  right: 0;
}

.prev {
  left: 0;
}

.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.9);
}
 
</style>
