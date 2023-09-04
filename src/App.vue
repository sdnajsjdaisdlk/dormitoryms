<template>
  <div id="app">
   <router-view></router-view>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Login from "@/views/Login";

export default {
  name: 'app',
  components: {
    HelloWorld,
    Login,
  }
}
</script>

<style>
</style>
