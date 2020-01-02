<template>
   <div id="parent">
       <div class="t">
           <h1> Coming soon...</h1>
       </div>
       <div>
           <i>mdi mdi-twitter</i>
       </div>
       
   </div>

</template>

<style scoped>
   div #parent{ 
        display:flex;
        background: #00091B;
        height: 70vh;
        position: relative
    }

    .t h1{
      
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%);
     color: white;
    }
</style>