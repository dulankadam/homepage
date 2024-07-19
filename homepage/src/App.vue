<template>
  <div id="app">
    <HeaderBarVue/>
    <HomePageVue/>
    <!-- <Header></Header> -->
<Fotter/>
  </div>
</template>

<script>

import Header from './components/Header.vue';
import Fotter from './components/Fotter.vue';
import HomePageVue from './components/HomePage.vue';
import HeaderBarVue from './components/HeaderBar.vue';


export default {
  name: 'App',
  components: {
    Header,
    HeaderBarVue,
    HomePageVue,
   Fotter
   
  },
};
</script>
