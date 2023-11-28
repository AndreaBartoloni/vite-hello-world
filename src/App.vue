<script>
import HelloWorld from './components/HelloWorld.vue'
import hero from './components/hero.vue'


export default{
  components: {
    HelloWorld, 
    hero
  }
}
</script>

<template>

  <header>
    <div>
      <p>Logo</p>
    </div>
    <div>
      <p>Logo</p>
    </div>
    <div>
      <p>Logo</p>
    </div>
  </header>
  
  
  <hero/>
  <HelloWorld/>
</template>

<style scoped>
  header{
    background-color: white;
    height: 50px;
    top: 0;
    position: relative;
    display: flex;
    align-items: center;
  }
  header > div {

    width: 33%;
  }
  p{
    color: black;
  }
</style>
