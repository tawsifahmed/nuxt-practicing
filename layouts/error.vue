<template> 
    <div class="electric-animation"> 
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

.electric-animation:hover {
  position: relative;
  animation: electric 3s linear infinite;
  cursor: default;
  transition: 3s;
}

@keyframes electric {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(10deg);
    color: aquamarine;
  }
}
</style>