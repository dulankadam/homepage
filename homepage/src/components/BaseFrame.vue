<template>
    <div :class="{ 'mobile-layout': isMobile }">
      <!-- Your content -->
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        isMobile: false,
      };
    },
    created() {
      this.checkScreenSize();
      window.addEventListener('resize', this.checkScreenSize);
    },
    methods: {
      checkScreenSize() {
        this.isMobile = window.innerWidth <= 600;
      },
    },
    beforeDestroy() {
      window.removeEventListener('resize', this.checkScreenSize);
    },
  };
  </script>
  
  <style>
  .mobile-layout {
    flex-direction: column;
  }
  </style>