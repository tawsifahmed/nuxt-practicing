<template> 
    <div class="mid"> 
       <Nuxt/>
    </div> 
</template> 

<script>
    export default {
        layout: "error-layout",
    };
</script>

<style>
.mid{
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 100px;
    height: 100vh;
}
</style>