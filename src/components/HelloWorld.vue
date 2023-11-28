<script>
export default{

  data() {
    return {
      sliderImg: [
        {
          img: "17671.jpg",
          title: "ciao"
        },
        {
          img: "17670.jpg",
        },
        {
          img: "17675.jpg",
        }
      ], 
      startImg: 0
    }
  },

  methods: {
    next(){
      if(this.startImg < this.sliderImg.length - 1){
        this.startImg++;
      }
    },
    prev(){
      if(this.startImg > 0){
        this.startImg--;
      }
        
    }
  },

}

</script>

<template>
  <div>
    <div class="container-img">
      <img :src="sliderImg[startImg].img">
    </div>
    <button @click="prev()">prev</button>
    <button @click="next()">next</button>
  </div>
</template>

<style scoped>
.container-img{
  margin: 50px;
}
.container-img > img{
  width: 50%;
}

</style>
