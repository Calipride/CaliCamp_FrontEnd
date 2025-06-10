<template>
    <div>
      <NavBar />
      <br>
      <SearchForm />
      <br>
      <FootBar />
      </div>
    
  </template>
  
  <script>
  import NavBar from './NavBar.vue'
  import SearchForm from './SearchForm.vue'
  import FootBar from './FootBar.vue';
  
  export default {
    components: {
      
      NavBar,
      SearchForm,
      FootBar
      
    },
    
  };
  </script>
  
  <style scoped>
  .user-page {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    
  }
  </style>