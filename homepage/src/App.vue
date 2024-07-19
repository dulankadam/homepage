<template>
  <div id="app">
  <Fotter/>
  
  </div>
</template>

<script>
import bodyVue from './components/body.vue';

import Header from './components/Header.vue';
import HeaderBarVue from './components/HeaderBar.vue';
import Body from './components/body.vue';
import Fotter from './components/Fotter.vue';


export default {
  name: 'App',
  components: {
   Fotter
  
  },
};
</script>
