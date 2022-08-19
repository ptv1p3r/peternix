<template>
  <!--  <img alt="Vue logo" src="./assets/logo.png">-->
  <b-container fluid="sm">
    <div id="pageWrap" :style="{ 'background-image': 'url(' + require('../src/assets/intro-bg.jpg') + ')' }">
      <site-header></site-header>
      100% wide until small breakpoint
      <HelloWorld msg="Welcome to Your Vue.js App"/>
      <site-footer></site-footer>
    </div>
  </b-container>
  <!--  <b-container fluid="md">-->
  <!--    100% wide until medium breakpoint-->
  <!--  </b-container>-->
  <!--  <b-container fluid="lg">-->
  <!--    100% wide until large breakpoint-->
  <!--  </b-container>-->
  <!--  <b-container fluid="xl">-->
  <!--    100% wide until extra large breakpoint-->
  <!--  </b-container>-->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import siteHeader from './components/Header.vue'
import siteFooter from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    siteHeader,
    HelloWorld,
    siteFooter
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

}

body {
  display: block;
  text-size-adjust: 100%;
  word-wrap: break-word;
  color: rgb(168, 160, 149);
  margin: 0;
  padding: 0;
  border-color: #736b5e;
}

#pageWrap {
  box-sizing: border-box;
  padding-top: 73px;
}
</style>
