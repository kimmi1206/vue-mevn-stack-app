<template>
  <v-app>
    <Header />
    <NavBar />
    <Aside />
    <v-main>
      <router-view />
    </v-main>

    <Footer />
  </v-app>
</template>

<script>
import Header from "./components/Header.vue";
import NavBar from "./components/NavBar.vue";
import Footer from "./components/Footer.vue";
import Aside from "./components/Aside.vue";

export default {
  name: "App",
  data: () => ({}),
  components: {
    Header,
    NavBar,
    Aside,
    Footer,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

@media (max-width: 575px) { 
/* @media screen and (max-height: 450px) { */
    #lateral {
        display: none !important;
    }
 
}

/* // Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { 
    
 }

/* // Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { 
    
 }

/* // Large devices (desktops, 992px and up) */
@media (min-width: 992px) { 
    
 }

/* // X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { 
    
 }

/* // XX-Large devices (larger desktops, 1400px and up) */
@media (min-width: 1400px) { 
    
 }

</style>
