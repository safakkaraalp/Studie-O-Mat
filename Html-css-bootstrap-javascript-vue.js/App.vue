<template>
    <div id="app">
      <HeaderComponent />
      <SliderComponent />
    </div>
  </template>
  
  <script>
  import HeaderComponent from './components/HeaderComponent.vue'
  import SliderComponent from './components/SliderComponent.vue'
  
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      SliderComponent
    }
  }
  </script>
  
  <style>
  /* Add your global styles here */
  </style>
  