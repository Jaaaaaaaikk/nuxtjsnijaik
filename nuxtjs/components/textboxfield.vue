
<template>
    <input type="text" v-bind="value" :placeholder="placeholder">
  </template>
  
  <script>
  export default {
    props: {
      value: String, // Value of the textbox
      placeholder: String // Placeholder text for the textbox
    }
  }
  </script>
  
  <style scoped>
  /* Add component-specific styles here if needed */
  </style>
  