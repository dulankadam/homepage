<template>
  <div id="app">
    <HeaderBarVue/>
  
  
  </div>
</template>

<script>
import GlobalEdulink from './components/Header.vue';
import Fotter from './components/Fotter.vue';
import Header from './components/Header.vue';
import HeaderBarVue from './components/HeaderBar.vue';



export default {
  name: 'App',
  components: {
    Header,
    HeaderBarVue
  
  },
};
</script>
