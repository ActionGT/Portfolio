<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <LandingPage msg =" GT DEV Portfolio"/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import LandingPage from '@/components/LandingPage.vue';

export default {
  name: 'HomeView',
  components: {
    // HelloWorld,
    LandingPage
  }
}
</script>
