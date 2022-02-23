<template>
  <div class="home">
   <!-- 1.疫情图片 -->
   <img src="../assets/images/1.jpg" width="100%" alt="">
    <CovInfo/>
  </div>
</template>

<script>
import CovInfo from "./CovInfo/CovInfo.vue";
export default {
  name: 'Home',
  // data () {
  //   return {
  //     // msg: 'Welcome to Your Vue.js App'
  //   }
  // },
  components:{
    CovInfo,
  }
}
</script>


<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
