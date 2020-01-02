<template>
  <div id="app">
   
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nav {
  padding: 30px;
}
.green-underline {
  width: 3vw;
  border-top: 4px solid #49a347;
}
.list-star{
    list-style-image: url('../public/star.png');
}

</style>
