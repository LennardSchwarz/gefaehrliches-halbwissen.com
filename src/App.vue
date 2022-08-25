<template>
  <div id="app">
    <Body class="body" />
    <particles-bg type="lines" color="#ffffff" :num=300 :canvas="{backgroundColor:'#ffffff'}" :bg="true"/>
  </div>
</template>

<script>
import { ParticlesBg } from "particles-bg-vue";
import Body from "./components/Body.vue";
export default {
  name: "App",
  components: {
    Body,
    ParticlesBg
    
}
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>