<template>
  <div id="app">
    <img  class="logo" src="./assets/logo.png" alt="logo">

    <!-- 3--使用组件标签 -->
    <!-- <Kl02/> -->
    <Kl02>
      kkkk
    </Kl02>
    <router-view/>
  </div>
</template>

<script>
  //1--引入组件
  import Kl02 from './components/Kl02.vue'


export default {
  name: 'App',

  //第二： 映射组件标签
  components:{
    Kl02,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.logo{
  width: 100px;
  height: 16.875rem;
}
</style>
