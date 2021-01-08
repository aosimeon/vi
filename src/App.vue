<template>
  <Header/>
  <Main/>
  <SocialLinks/>
  <MainNav/>
</template>

<script>
import HelloWorld from './components/Header.vue'
import Header from "@/components/Header";
import Main from "@/components/Main";
import SocialLinks from "@/components/SocialLinks";
import MainNav from "@/components/MainNav";

export default {
  name: 'App',
  components: {
    Header,
    Main,
    SocialLinks,
    MainNav,
  }
}
</script>

<style lang="scss">
body {
  background: linear-gradient(
          90deg
      , rgb(189, 15, 77) 0%
      , rgb(189, 15, 77) 50%
      , rgb(203, 41, 100) 50%
      , rgb(203, 41, 100) 100%
  );
  margin:0;
  padding: 0;
}
#app {
  position: relative;
  font-family: 'Raleway', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin:0;
  padding: 0;
}
</style>
