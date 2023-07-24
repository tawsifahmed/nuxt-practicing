<template> 
    <div> 
     <h1>{{error.statusCode}} - <span class="red-text">Not found</span></h1>
    </div> 
  </template> 

<script>
    export default {
      layout: "error-layout",
      props: {
      error: {
          type: Object,
          default: null,
      },
    },
    head(){
      return{
        title: 'Error Page',
        meta:[
          {
            hid: 'error',
            name: 'error',
            content: 'This is the error page'
          },
        ],
      }
    },
  };
</script>

<style scoped>

.red-text{
    color: red;
    font-style: italic;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
</style>