<template>
  <v-app>
    <NavBar />
    <v-main class="kk">
      <!-- <router-link /> -->
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from './components/NavBar';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    NavBar,
    Footer
  },
  created(){
    console.log(window.innerHeight);
  },
  data: () => ({
    
  }),
  mounted (){
  },
};
</script>
