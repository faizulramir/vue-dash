<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <h4 for="top-bar-title">{{ topBarTitle.toUpperCase() }}</h4>
    </div>
  </nav>
</template>
  
<script>
  
  export default {
    name: 'TopBar',
    props: {
      topBarTitle: {
        type: String,
        default: 'Empty',
      },
    },
    data() {
      return {
        
      }
    },
    methods: {
      
    }
  }
  </script>
  
  <style>
    .container {
      padding-left: 10px !important; margin-left: 0 !important;
      height: 60px;
    }
  </style>
  