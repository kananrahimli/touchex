<template>
  <div id="app">
    <coming-soon></coming-soon>
    <router-view/>
  </div>
  
</template>
<script>
import ComingSoon from './components/ComingSoon.vue'
export default {
  components:{
    ComingSoon
  }
}
</script>
<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@800&display=swap');

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: 'Manrope', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}

body{
  background:#ffffff;
}


</style>
