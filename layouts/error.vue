<template> 
    <div> 
     <h1>{{error.statusCode}} Not found</h1>
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
    }
  };
</script>