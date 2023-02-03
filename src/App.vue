<template>
<!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <SideBar></SideBar>
    <router-view></router-view>
<!--    <HomeComponent></HomeComponent>-->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HomeComponent from "@/components/HomeComponent";
import SideBar from "@/components/SideBar";

export default {
  name: 'App',
  components: {
    // HelloWorld
    //   HomeComponent,
      SideBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

side-bar {

}

</style>
