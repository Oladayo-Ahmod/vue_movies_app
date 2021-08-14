<template>
  <div id="app">
    <!-- <router-view/> -->
	<router-link to="/">
		<h3>Home</h3>
	<router-link>
		<Home />


  </div>
</template>

<script>
import Home from '@/Views/Home.vue'
/* eslint-disable */
export default {
  name: 'App',
  components:{
	Home,
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
</style>
