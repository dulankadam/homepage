<template>
  <div id="app">
    <Header></Header>
<Fotter/>
  </div>
</template>

<script>

import Header from './components/Header.vue';
import Fotter from './components/Fotter.vue';


export default {
  name: 'App',
  components: {
    Header,
   Fotter
   
  },
};
</script>
