<template>
  <div id="app">
    <HeaderBarVue/>
    <NavBarVue></NavBarVue>
    <Header></Header>
    <HeaderContents/>
   <HomePageVue></HomePageVue>
    
    <Fotter/>
  </div>
</template>

<script>

import Header from './components/Header.vue';
import Fotter from './components/Fotter.vue';
import HomePageVue from './components/HomePage.vue';
import HeaderBarVue from './components/HeaderBar.vue';
import body from './components/body.vue';
import NavBarVue from './components/NavBar.vue';
import HeaderContents from './components/HeaderContents.vue';

export default {
  name: 'App',
  components: {
    Header,
    body,
    NavBarVue,
    HeaderBarVue,
    HomePageVue,
   Fotter,
   HeaderContents
   
  },
};
</script>
