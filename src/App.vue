<template>
  <div>
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
#app {
  /* display: grid; */
  font-family: "Raleway", sans-serif;
  margin: 0 auto;
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  /* text-align: center; */
  /* align-content: center;
  color: #2c3e50; */
}
body {
  margin: 0;
}
</style>
